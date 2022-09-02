# Classifying fruits
While I was delving into various classification problems, I came across this interesting read: https://medium.com/@ocktavia/fruits-lovers-solving-a-simple-classification-problem-with-python-e63ae067422c

Essentially the problem statement was this:
> Can we train a classifier to distinguish between Apples, Lemons, Oranges and Mandarin oranges?

## Preparing the Data

A brief description of the data:

<img src="https://github.com/jjasim/fruits-classification-with-npp/blob/main/images/data.PNG" width="300" height="100">
<img src="https://github.com/jjasim/fruits-classification-with-npp/blob/main/images/Table.PNG" width="300" height="100">

The dataset has 7 features, of which I believe the mass, width, height and colour_score will be important in identifying the fruit_name. 

<img src="https://github.com/jjasim/fruits-classification-with-npp/blob/main/images/distributions.png" width="300" height="300">

The mass, height and colour_score seem to be fairly gaussian. Mass and width as well as mass and height seems to have a linear relationship.

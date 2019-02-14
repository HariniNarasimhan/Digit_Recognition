# Digit_Recognition
The MNIST dataset that is used to classify and predict the digits from 0 to 9. The hand written images of numerals from 0 to 9 
are the data sets avaliable in keras as MNIST. The goal is to predict the numeral based on the hand written image.
## Prerequisites
The package needed are the following
keras
numpy
pandas
matplotlib

## Install the following packages
```
pip install numpy
pip install pandas
pip install matplotlib
pip install tensorflow
pip install keras
```

## Dataset

The dataset is in the format of csv (Comma separated values) here. The train.csv is the data file and the test.csv being the test file.
The training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn. The rest of the columns contain the pixel-values of the associated image. 784 columns make the image of size (28x28). We have 42000 images and so the train.csv has 42,0000 rows with 785 columns.
The test data set comprises of the 28000 images i.e., 28,0000 rows of each with 784 columns. The "label" column is to be predicted.

You can also load data using keras as,

```
from keras.datasets import mnist

(x_train, y_train), (x_test, y_test) = mnist.load_data()
```
## Result

The result of our model has gained the top 24% in the kaggle competition "Digit Recognizer" with accuracy of 0.9947

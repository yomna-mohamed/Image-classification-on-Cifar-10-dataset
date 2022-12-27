# Image-classification-on-Cifar-10-dataset
Assignment 1 for Computer vision course using cifar10 apply image classification models like KNN, logistic regression, LineaSVC and SVC with RBF kernel
 Overview This Project to know the basics of data loading and preparation using Cifar10 dataset implemented with different classification model build KNN from Scratch and try different modes of SVM and determine the best performance.

## DataSet

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.



## Dataset Preparation 
Download dataset from keras using :Data=tf.keras.datasets.cifar10.load_data() Split the data into train and test and validation Visualize five samples from each class then applying Normalization on the data

# Models
## KNN
using Euclidean distance to measure th distance between every point 

Drawing the confusion matrix and evaluate by accuracy score
## LR
Using logistic regression from sklearn and build OvR from scratch to achieve multi-class classfication how to do this by train a binary classifier for each class therefore need 10 models to obtain the predicted class by select the argmax

## Add regularization term L1

## Adding gamma with different range

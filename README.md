# Image-recognition-using-CNN
image recognition using CNN on CIFAR-10 dataset 
CIFAR-10 Image Recognition Project

This project demonstrates image recognition using the CIFAR-10 dataset and a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)

## Introduction

The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 different classes, with 6,000 images per class. The dataset is divided into 50,000 training images and 10,000 testing images. This project uses a Convolutional Neural Network (CNN) to classify the images into their respective categories.

## Dataset

The CIFAR-10 dataset includes the following classes:
1. Airplane
2. Automobile
3. Bird
4. Cat
5. Deer
6. Dog
7. Frog
8. Horse
9. Ship
10. Truck

More information about the dataset can be found [here](https://www.cs.toronto.edu/~kriz/cifar.html).

## Model Architecture

The CNN model consists of the following layers:
1. Convolutional Layer with 32 filters, 3x3 kernel, and ReLU activation
2. MaxPooling Layer with 2x2 pool size
3. Convolutional Layer with 64 filters, 3x3 kernel, and ReLU activation
4. MaxPooling Layer with 2x2 pool size
5. Convolutional Layer with 64 filters, 3x3 kernel, and ReLU activation
6. Flatten Layer
7. Dense Layer with 64 units and ReLU activation
8. Output Dense Layer with 10 units and softmax activation

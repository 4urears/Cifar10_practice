# CIFAR-10 Image Classification

## Introduction

Welcome to the CIFAR-10 Image Classification project! This repository contains code for image classification on the CIFAR-10 dataset using two different convolutional neural network (CNN) architectures implemented in Keras. The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 different classes.
## Conv2D Layer

The `Conv2D` layer is a 2D convolutional layer that is commonly used in image processing tasks. It applies convolutional filters to input data, allowing the network to learn spatial hierarchies of features. In the provided models, `Conv2D` layers are used with different filter sizes and activation functions to extract features from the CIFAR-10 images.

## MaxPooling2D Layer

The `MaxPooling2D` layer is a downsampling operation commonly used in convolutional neural networks (CNNs). It reduces the spatial dimensions of the input volume, retaining the most important information. In the given models, `MaxPooling2D` layers are applied to reduce the spatial resolution of the feature maps obtained from the convolutional layers.

## Flatten Layer

The `Flatten` layer is used to flatten the input data, converting it from a multi-dimensional array into a one-dimensional array. In the models, this layer is applied after the convolutional and pooling layers to prepare the data for the fully connected layers.

## Dense Layer

The `Dense` layer represents a fully connected layer, where each neuron is connected to every neuron in the previous layer. It is used for learning global patterns and relationships in the data. In the provided models, `Dense` layers with varying numbers of units and activation functions are used to create the fully connected part of the neural network.

## Softmax Activation

The `Softmax` activation function is commonly used in the output layer of a classification model. It converts the raw output scores into probability distributions over multiple classes. In the models, the final `Dense` layer uses the `Softmax` activation to produce probability scores for each of the 10 classes in the CIFAR-10 dataset.

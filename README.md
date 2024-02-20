# MNIST-hand-writing

## Introduction

This is a simple project to recognize hand writing digits using the MNIST dataset. The project is implemented using `torch` and `torchvision` libraries.

## Method


### Fully-connected Neural Network

The project uses a simple feedforward neural network with 3 hidden layers. The input layer has 784 neurons, the first hidden layer has 128 neurons, the second hidden layer has 32 neurons, and the third hidden layer has 16 neurons. The output layer has 10 neurons, each representing a digit from 0 to 9.

### Convolutional Neural Network

The project also uses a convolutional neural network with 2 convolutional layers and 2 fully connected layers. The first convolutional layer has 32 filters, and the second convolutional layer has 64 filters. Final accuracy of the model is 99.18%.


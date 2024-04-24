# MNIST Neural Network From Scratch
This repository contains Python code for implementing a simple neural network from scratch using only NumPy and math libraries. The neural network is trained and tested on the MNIST dataset, a popular benchmark dataset for handwritten digit recognition.

# Overview
The MNIST dataset consists of 28x28 pixel grayscale images of handwritten digits (0-9). The goal of this project is to train a neural network to correctly classify these digits.

The neural network architecture implemented here consists of an input layer, a hidden layer, and an output layer. The input layer has 784 neurons (28x28 pixels flattened), the hidden layer has 128 neurons, and the output layer has 10 neurons corresponding to the 10 possible digit classes.

# Explanation
The Neural Network will have a simple two-layer architecture. Input layer  a[0] will have 784 units corresponding to the 784 pixels in each 28x28 input image. A hidden layer a[1] will have 10 units with ReLU activation, and finally, our output layer a[2] will have 10 units corresponding to the ten-digit classes with softmax activation.

**Forward Propogation**


![image](https://github.com/Quiirky-codes/MNIST_neural_network/assets/111241572/3758bb43-7c77-4e3b-a4bd-aea8b8990f08)



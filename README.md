# MNIST Neural Network From Scratch
This repository contains Python code for implementing a simple neural network from scratch using only NumPy and math libraries. The neural network is trained and tested on the MNIST dataset, a popular benchmark dataset for handwritten digit recognition.

# Overview
The MNIST dataset consists of 28x28 pixel grayscale images of handwritten digits (0-9). The goal of this project is to train a neural network to correctly classify these digits.

The neural network architecture implemented here consists of an input layer, a hidden layer, and an output layer. The input layer has 784 neurons (28x28 pixels flattened), the hidden layer has 128 neurons, and the output layer has 10 neurons corresponding to the 10 possible digit classes.

# Explanation
The Neural Network will have a simple two-layer architecture. Input layer  a[0] will have 784 units corresponding to the 784 pixels in each 28x28 input image. A hidden layer a[1] will have 10 units with ReLU activation, and finally, our output layer a[2] will have 10 units corresponding to the ten-digit classes with softmax activation.

* **Forward Propagation**


  ![image](https://github.com/Quiirky-codes/MNIST_neural_network/assets/111241572/3758bb43-7c77-4e3b-a4bd-aea8b8990f08)

* **Backward Propagation**


  ![image](https://github.com/Quiirky-codes/MNIST_neural_network/assets/111241572/48f173c1-6aa4-457d-9621-063ae84763c6)


* **Parameter Updates**


  ![image](https://github.com/Quiirky-codes/MNIST_neural_network/assets/111241572/04a67ca2-cf0a-4e39-866c-7ad818e4d190)


* **Vars and Shapes**

  Forward prop


  ![Screenshot 2024-04-24 153422](https://github.com/Quiirky-codes/MNIST_neural_network/assets/111241572/b6b5b924-fa19-4c6a-b7c9-e0fab04ee64b)


  Back prop


  ![Screenshot 2024-04-24 153431](https://github.com/Quiirky-codes/MNIST_neural_network/assets/111241572/b5da5d0a-19d4-4b18-b555-bc34dc717b9d)


# Results

After training the neural network on the MNIST dataset for 600 iterations, the model achieved an accuracy of **95%** on the training set and a final training accuracy of **98%**.








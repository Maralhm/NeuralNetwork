# Neural Network From Scratch

This project focuses on building a neural network from the ground up to perform multi-class classification on a synthetic dataset. The primary goal is to gain a deep understanding of the fundamental components of a neural network and how it learns to make predictions.

## Overview

In this project, we cover the following key steps:

**1. Generating Synthetic Data:**

We create a synthetic dataset using the scikit-learn library. This dataset consists of 500 samples with 2 features, with a clear distinction between two classes. Visualizing the dataset helps us understand the data distribution.
**2. Defining the Neural Network:**

We define a custom neural network class, NeuralNetwork, which represents our neural network architecture. This class includes methods for initializing the network, defining activation functions (sigmoid and softmax), implementing forward and backward propagation, and making predictions.
**3. Training the Neural Network:**

We implement a training loop to train the neural network. This loop performs forward and backward propagation on the training data and updates the model's weights and biases based on the calculated gradients. Periodically, we monitor the training progress by printing the loss.
**4. Evaluating the Model:**

After training, we evaluate the model's performance on a separate test set. We calculate the accuracy of the model's predictions compared to the true test labels to assess its effectiveness.
**5.Visualizing the Decision Boundary:** 

To gain insights into how well the model separates different classes in the data, we visualize the decision boundary of the trained model using a custom function. This visualization aids in understanding the model's classification capabilities.

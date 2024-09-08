# MNIST Handwritten Digit Classification

This project demonstrates how to classify handwritten digits from the MNIST dataset using a neural network built with deep learning
techniques. The MNIST dataset is a widely used benchmark in 
the field of machine learning and consists of 70,000 28x28 grayscale images of handwritten digits (0-9).

The goal of this project is to classify handwritten digits from the MNIST dataset using a neural network. This involves training 
a model to recognize patterns in images of digits and then evaluating its performance on unseen data.

# Model Architecture

## The neural network architecture used in this project is as follows:

Input Layer:  (28x28 pixels, flattened)

Hidden Layer 1: 50 units, ReLU activation

Hidden Layer 2: 50 units, ReLU activation

Output Layer: 10 units (one for each digit), Softmax activation

###  Steps follwed in this Process :

Training

Load MNIST dataset using TensorFlow keras

Normalize the images.

Train the model using the training data.

predict the model using test data 

evaluate the model and get the accuracy

visualize the confusion matrix

## Finally build a predictive system for the user if they want test the model

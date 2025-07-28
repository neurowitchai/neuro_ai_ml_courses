# Module 2: Basics of Deep Learning

This module dives into the fundamental mechanics of neural networks and how they learn. You'll explore the inner workings of gradient descent and backpropagation, understand common training issues like the vanishing gradient problem, and see how activation functions help address them. Through practical labs, you'll observe how these concepts impact model performance in real time.

## Topics Covered

- Gradient Descent
- Backpropagation
- Vanishing Gradient Problem
- Activation Functions

## Notebook(s)

- `backpropagation.ipynb` – Walks through the backpropagation algorithm.
- `activation_functions.ipynb` – Compares different activation functions and their effects.

## Learning Objectives

By the end of this module, you should be able to:

- Explain how gradient descent is used to optimize neural networks  
- Describe the process and role of backpropagation  
- Identify challenges posed by the vanishing gradient problem  
- Evaluate the impact of different activation functions on model training  

## Resources

- [Course link](https://www.coursera.org/learn/introduction-to-deep-learning-with-keras)
- Optional reading: [CS231n – Neural Networks Part 1: Setting up the data and the model](http://cs231n.github.io/neural-networks-1/)

## Did You Know?
* Gradient descent is an iterative optimization algorithm for finding the minimum of a function.
* A large learning rate can lead to big steps and miss the minimum point.
* A small learning rate can result in extremely small steps and cause the algorithm to take a long time to find the minimum point.
* Neural networks train and optimize their weights and biases by initializing them to random values. Subsequently, we repeat the following process in a loop.
* First, we calculate the network output using forward propagation. Second, we calculate the error between the ground truth and the estimated or predicted output of the network. Third, we update the weights and the biases through backpropagation. Last, we repeat the previous three steps until the number of iterations or epochs is reached or the error between the ground truth and the predicted output is below a predefined threshold.
* The vanishing gradient problem is caused by the problem with the sigmoid activation function, which prevents neural networks from booming sooner.
* In a very simple network of two neurons only, the gradients are small, but more importantly, the error gradient with respect to w1 is very small.
* When we do backpropagation, we keep multiplying factors that are less than one by each other, so their gradients tend to get smaller and smaller as we keep moving backward in the network.
* Neurons in the earlier layers of the network learn very slowly compared to the neurons in the later layers.
* As the earlier layers are the slowest to train, the training process takes too long, and prediction accuracy is compromised.
* We don't use the sigmoid or similar functions as activation functions since they are prone to vanishing gradient problems.
* Activation functions perform a major role in training a neural network.
* You can use seven activation functions to build a neural network.
* Sigmoid functions are one of the most widely used activation functions in the hidden layers of a neural network.
* Hyperbolic tangent function is a scaled version of the sigmoid function, but it is symmetric over the origin.
* The ReLU function is the most widely used activation function when designing networks today, and its main advantage is that it doesn’t activate all neurons at the same time.
* Softmax function is ideally used in the output layer of the classifier, where we are trying to get the probabilities to define the class of each input.
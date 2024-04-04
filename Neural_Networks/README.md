# Assignment Overview

This assignment involves implementing various versions of a 3-layer neural network for nonlinear regression using different deep learning frameworks and approaches. Below is a breakdown of each part of the assignment:

[Link to Colab 1](https://colab.research.google.com/drive/1s7a_XqSSw9U5ISvK1ysuexE3vz817Aln?usp=sharing)

[Link to Colab 2](https://colab.research.google.com/drive/1ezkKtEtOxvTKfkVWlagFjGwS09oTQ48E?usp=sharing)

[Link to Video Demo .mov](https://drive.google.com/file/d/1L4MvxTB6p4Umw1vxeMHi-Rn66D6cmVhj/view?usp=sharing)

## a) Numpy Only 3-Layer Neural Network for Nonlinear Regression

### Steps:
1. Data Generation: Generate synthetic data using a nonlinear equation with three variables.
2. Model Definition: Implement a 3-layer neural network from scratch using numpy. Define appropriate nonlinear activation functions and set the number of neurons in each hidden layer.
3. Training Loop: Perform manual backpropagation and gradient descent. Implement the training loop, displaying loss and epochs during training.
4. Visualization: Plot the results, including the final output and loss over epochs.

## b) PyTorch from Scratch 3-Layer Neural Network

### Steps:
1. Data Generation: Generate synthetic data using a nonlinear equation.
2. Model Definition: Create a 3-layer neural network from scratch using PyTorch without using built-in layer functionality. Implement the forward pass, backward pass (backpropagation), and gradient descent.
3. Training Loop: Train the model and display loss and epochs during training.
4. Visualization: Plot the results, including the final output and loss over epochs.

## c) PyTorch Classes-Based 3-Layer Neural Network

### Steps:
1. Data Generation: Generate synthetic data.
2. Model Definition: Define a 3-layer neural network using PyTorch's built-in layer functionality and backpropagation. Utilize PyTorch's classes to create the model architecture.
3. Training Loop: Train the model using PyTorch's training utilities.
4. Visualization: Plot the results, including the final output and loss over epochs.

## d) PyTorch Lightning Version

### Steps:
1. Data Generation: Generate synthetic data.
2. Model Definition: Define the 3-layer neural network using PyTorch Lightning's lightning module.
3. Training Loop: Utilize PyTorch Lightning's lightning trainer for training and evaluation.
4. Visualization: Plot the results, including the final output and loss over epochs.

## e) TensorFlow Variants

4D Plotting with Matplotlib
Generate a 4D plot to visualize the relationship between the input feature, actual output, predicted output, and error magnitude. Utilize Matplotlib's capabilities to create the plot.

Tensorflow only from scratch not using high level api  of the same

Tensorflow only with builtin layers of the same

Use functional api high level api  of tensorflow for the same

Tensorflow only but using high level api

## h) JAX Implementation

Implement the entire pipeline using JAX, including data generation, model definition, training loop, and visualization. Utilize JAX's automatic differentiation capabilities for backpropagation.


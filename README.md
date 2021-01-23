# Planar_data_classification

Here we want to implement a neural network framework for data classification.

First, after loading the data, we will perform logistic regression from sklearn's built-in functions. Since the data  is not linearly separable, simple logistic regression does not perform well.

The general methodology to build a Neural Network is to:

1. Define the neural network structure ( # of input units,  # of hidden units, etc). 
2. Initialize the model's parameters
3. Loop:
    - Implement forward propagation
    - Compute loss
    - Implement backward propagation to get the gradients
    - Update parameters (gradient descent)


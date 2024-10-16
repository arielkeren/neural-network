# Neural Network

A customizable feedforward neural network.

## Features

### Overview

The neural network is highly customizable, allowing to piece together a network, designed for a specific use case.<br>
Properties that can be modified:
- **Loss Function** - mean squared error, binary cross entropy, categorical cross entropy.
- **Layer initialization** - He, Xavier.
- **Layer activation** - ReLU, sigmoid, softmax.
- **Layer neurons** - any positive integer.

### Specialized Models

There are some specialized models, with added accuracy testing methods, available for faster implementation for general use cases:
- **Binary Classifier**<br>
  Used for binary classification problems - classification into 2 different classes.<br>
  Initialized with:
  - Output layer of 1 neuron with sigmoid activation and Xavier initialization.
  - Binary cross entropy.
- **Classifier**<br>
  Used for classification problems.<br> 
  Initialized with:
  - Output layer with softmax activation and Xavier initialization.
  - Categorical cross entropy.
- **Regressor**<br>
  Used for regression problems.<br> 
  Initialized with:
  - Output layer with linear activation and Xavier initialization.
  - Mean squared error.
- **Perceptron**<br>
  Used for simple classification or regression problems.<br>
  Allows only a single layer, in order mimic a perceptron.<br>
  Initialized with:
  - Output layer of 1 neuron.
- **Linear Regressor**<br>
  Used for simple regression problems.<br>
  Allows only a single layer, in order to mimic a perceptron.<br>
  Initialized with:
  - Output layer of 1 neuron with linear activation and zero initialization.
  - Mean squared error.
- **Logistic Regressor**<br>
  Used for simple binary classification problems.<br>
  Allows only a single layer, in order to mimic a perceptron.<br>
  Initialized with:
  - Output layer of 1 neuron with sigmoid activation and Xavier initialization.
  - Binary cross entropy.

### Utility Functions

For ease of use, some utility functions are prepared for splitting train and test data, and for reading data from binary files.

### Premade Examples

To provide some examples, the different specialized models have been used for various problems, such as handwritten digit recognition, iris classification, gender binary classification, height linear regression, OR logistic regression, function approximation.

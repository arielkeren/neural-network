# Neural Network

A customizable feedforward neural network.

## Features
### Overview
The neural network is highly customizable, allowing to piece together a network, designed for a specific use case.<br>
Properties that can be modified:
* **Loss Function** - mean squared error, binary cross entropy, categorical cross entropy.
* **Layer initialization** - He, Xavier.
* **Layer activation** - ReLU, sigmoid, softmax.
* **Layer neurons** - any positive integer.

### Specialized Models
There are a few specialized models available for faster implementation for general use cases:
* **Binary Classifier**<br>
  Used for binary classification problems - classification into 2 different classes.<br>
  Initialized with:
  1. Output layer of 1 neuron with sigmoid activation and Xavier initialization.
  2. Binary cross entropy.
* **Classifier**<br>
  Used for classification problems.<br> 
  Initialized with:
  1. Output layer with softmax activation and Xavier initialization.
  2. Categorical cross entropy.
* **Perceptron**<br>
  Used for simple classification or regression problems.<br>
  Allows only a single layer to mimic a perceptron.<br>
  Initialized with:
  1. Output layer of 1 neuron.
* **Linear Regression**<br>
  Used for simple regression problems.<br>
  Allows only a single layer to mimic a perceptron.<br>
  Initialized with:
  1. Output layer of 1 neuron with linear activation and zeros initialization.
  2. Mean squared error.
* **Logistic Regression**<br>
  Used for simple binary classification problems.<br>
  Allows only a single layer to mimic a perceptron.<br>
  Initialized with:
  1. Output layer of 1 neuron with sigmoid activation and Xavier initialization.
  2. Binary cross entropy.


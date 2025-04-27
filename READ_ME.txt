                                        ----------------------------------------
                                          Simple MLP Neural Network in Python
                                        ----------------------------------------
## Overview
This repository contains a Python implementation of a basic Multi-Layer Perceptron (MLP) neural network. It demonstrates the key concepts behind neural networks such as layers, neurons, weights, biases, and activation functions. The code allows you to configure the network architecture and run it with custom input values.

The neural network uses a sigmoid activation function and is initialized with random weights and biases. It computes outputs based on the inputs passed to it by performing forward propagation.

---

## Features

- Customizable network structure (number of layers and neurons in each layer).

- Sigmoid activation function for non-linear transformations.

- Simple forward propagation from input to output.

---

## How to Use :

The script will prompt you to input the following:

+ Number of inputs (features).

+ Number of hidden layers and neurons per hidden layer.

+ Number of output neurons.

+ Input values for the network.

After entering the required information, the network will process the inputs and print the final output based on the neural network structure and random weights.

---

## Code Explanation

- sigmoid(x):
This function implements the sigmoid activation function, which is used to introduce non-linearity into the network.

- neuron(inputs, weights, bias):
This function calculates the output of a single neuron given the inputs, weights, and bias. It returns the result of applying the sigmoid function to the weighted sum of inputs and bias.

- MLP class:
This class implements the Multi-Layer Perceptron (MLP). It includes:

+ Initialization: Random weights and biases are generated for each layer.

+ Forward propagation: The forward() method propagates the inputs through all layers to compute the final output.

---

## Example:

After running the script, you will be prompted to configure the network as follows:

yaml
Copier
Modifier
Number of inputs: 3
Number of hidden layers: 2
Number of neurons in hidden layer 1: 4
Number of neurons in hidden layer 2: 3
Number of output neurons: 1
Value of input 1: 0.5
Value of input 2: 1.2
Value of input 3: 0.8
The network will then output a result based on the inputs you provided and the network configuration.

---

## Contributions

Feel free to fork the repository and submit pull requests if you'd like to contribute to the development or enhancement of this project.

---

## License

This project is licensed under the MIT License - see the LICENSE file for details.
Neural Network for Test Score Prediction
This repository contains a Python implementation of a simple neural network that predicts test scores based on the number of hours a student sleeps and studies.

Dataset
The dataset used for training and testing the neural network consists of pairs of inputs (hours sleeping and hours studying) and corresponding outputs (test scores). The dataset is defined in the code.

Implementation Details
The neural network is implemented using numpy. It consists of an input layer, a hidden layer, and an output layer. The weights between the layers are randomly initialized. The network uses the sigmoid activation function.

The training process involves forward propagation to compute the output, followed by backward propagation to adjust the weights based on the prediction error. The network is trained for 1000 epochs, and the loss is printed every 100 epochs.

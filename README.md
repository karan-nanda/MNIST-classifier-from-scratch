# MNIST-classifier-from-scratch

## MNIST Classification Comparison: PyTorch vs. Numpy

This repository contains code for comparing the training and evaluation of a simple neural network for MNIST handwritten digit classification using both PyTorch and Numpy. The code demonstrates data fetching, model creation, training, evaluation, and a simple image recognition test.

## Introduction
In this repository, we provide Python code to illustrate the implementation of a neural network for classifying MNIST handwritten digits using both PyTorch and Numpy. The goal is to offer a side-by-side comparison of training and evaluating a neural network in both frameworks. The code covers data retrieval, model creation, training, evaluation, and a basic image recognition test.

Getting Started
To get started, you can clone this repository to your local machine using the following command:
``` bash
git clone (https://github.com/karan-nanda/MNIST-classifier-from-scratch.git)https://github.com/karan-nanda/MNIST-classifier-from-scratch.git
```
## Code Overview
The code is structured as follows:
- Data Fetching: The MNIST dataset is obtained from the official source using HTTP requests and saved locally.

- PyTorch Model: We define a simple neural network model using PyTorch. This model consists of two fully connected layers and a log-softmax activation function.

- Training in PyTorch: The PyTorch model is trained using stochastic gradient descent (SGD). Training loss and accuracy are tracked over iterations.

- Numpy Model: We replicate the PyTorch model using Numpy. This involves defining the forward pass and backpropagation.

- Training in Numpy: The Numpy model is trained using a similar approach to PyTorch, including forward and backward passes.

- Model Evaluation: We evaluate the PyTorch model's accuracy on the MNIST test dataset, achieving an accuracy of approximately 93.45%.

- Image Recognition Test: We test the trained model's recognition abilities by providing a simple handwritten digit image. The model successfully recognizes the digit.

## Results
The code provides a comparative analysis of training a neural network for MNIST classification using PyTorch and Numpy. Remarkably, the Numpy implementation achieved better accuracy during training (approximately 96.37%) compared to the PyTorch model. This result underscores the versatility and potential of Numpy for constructing neural networks, even in the presence of popular deep learning frameworks like PyTorch.

## License
This code is provided under the MIT License. You are free to use and modify it for your own projects.

Enjoy exploring the code and the world of neural network training in both PyTorch and Numpy!

# Implementing a Convolutional Neural Network Using Keras
This Jupyter notebook demonstrates how to build, train, and evaluate a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset using TensorFlow Keras.

## Overview

Handwritten digit recognition is a classic computer vision problem commonly used to benchmark machine learning models. This lab guides you through the entire machine learning lifecycle for this task, including:

- Defining the problem and identifying features and labels
- Importing and visualizing the MNIST dataset
- Data preprocessing (normalization and reshaping)
- Constructing a CNN architecture with multiple convolutional, batch normalization, activation, pooling, and output layers
- Training the CNN model with stochastic gradient descent and sparse categorical crossentropy loss
- Evaluating model performance on test data
- Visualizing predictions

## Dataset

The notebook uses the MNIST dataset, which contains 70,000 grayscale images of handwritten digits (0-9), each of size 28x28 pixels. The dataset is split into:

- 60,000 training images
- 10,000 testing images


## Usage

To run this notebook, make sure you have the following installed:

- Python 3.x
- TensorFlow (with Keras)
- NumPy
- Matplotlib
- Seaborn

You can execute the notebook cells in order to reproduce the results.

## Model Summary

The CNN has approximately 99,400 trainable parameters and achieves ~92.5% accuracy on the MNIST test set after one epoch.

---

Feel free to reach out if you have any questions or want to improve the model with additional epochs or architecture tweaks!

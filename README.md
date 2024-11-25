# Digit Recognition using Keras

## Overview
A deep learning model built with Keras to recognize handwritten digits from the MNIST dataset.

## Features
- Implementation of Convolutional Neural Network (CNN)
- MNIST dataset processing
- Real-time digit recognition
- High accuracy prediction

## Technologies
- Python
- Keras
- TensorFlow
- NumPy
- Matplotlib

## Installation
```bash
pip install tensorflow
pip install numpy
pip install matplotlib


## Project Overview
This project implements a Convolutional Neural Network (CNN) using Keras and TensorFlow to recognize handwritten digits from the MNIST dataset. The model achieves high accuracy through careful architecture design and optimization techniques.

## Dataset Information
- Dataset: MNIST Handwritten Digits
- Training samples: 60,000 images
- Testing samples: 10,000 images
- Image dimensions: 28x28 pixels (grayscale)
- Classes: 10 (digits 0-9)

## Model Components
  - Input Layer: 28x28x1 (grayscale images)
  - Convolutional Layers: Feature extraction with ReLU activation
  - MaxPooling Layers: Dimension reduction and feature selection
  - Dense Layers: Classification with batch normalization
  - Output Layer: 10 neurons with softmax activation

## Performance Metrics
  - Training Accuracy: 97%
  - Test Accuracy: 95%

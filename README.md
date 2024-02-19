
# Deep Learning Image Classification with CNN on CIFAR-10

## Project Overview
This project demonstrates the application of a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset. The model is built using TensorFlow and Keras, showcasing fundamental CNN components for effective image classification.

## Dataset
The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. It is split into 50,000 training images and 10,000 testing images.

## Model Architecture
The CNN model includes the following layers:
- Convolutional layers for feature extraction.
- MaxPooling layers for dimensionality reduction.
- Dense layers for classification.

## Requirements
- TensorFlow
- Matplotlib

## Usage
Run the script `cifar10_classification.py` to train the model and evaluate its performance on the CIFAR-10 dataset.

## Results
The model's performance is evaluated based on its accuracy on the test dataset. The training process plots the accuracy over epochs for both the training and validation sets.

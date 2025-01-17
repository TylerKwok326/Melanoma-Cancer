# Melanoma Classification Model

Overview
This project implements a Convolutional Neural Network (CNN) using PyTorch to classify skin lesion images as either benign (B) or malignant melanoma (M). The model achieves an accuracy of 87.9% on the test dataset.
Model Architecture
The CNN architecture consists of:

3 convolutional layers with increasing filter depths (32, 64, 128)
Max pooling after each convolutional layer
2 fully connected layers (512 units, 2 units)
ReLU activation functions
Softmax output layer for binary classification

Input images are processed at 50x50 pixels in grayscale 

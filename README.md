# part-2-cnn-computer-vision-25111021

# CNN Computer Vision Mini Project

## Project Overview

This project demonstrates the implementation of a Convolutional Neural Network (CNN) for image classification using TensorFlow/Keras.

The goal of this project is to understand:
- Image preprocessing
- CNN architecture
- Model training and evaluation
- Confusion matrix analysis
- Real-world computer vision applications

The dataset contains images representing different surface conditions:
- Dent
- Normal
- Scratch
- Stain


# Problem Type

This project is an Image Classification problem because the model predicts the class label of an input image.

The CNN model classifies images into one of four categories:
- Dent
- Normal
- Scratch
- Stain


# Dataset Exploration

## Number of Classes
The dataset contains 4 image classes:
- Dent
- Normal
- Scratch
- Stain

## Images Per Class
Each class contains approximately equal numbers of images, making the dataset relatively balanced.

## Image Dimensions
All images were resized to:
96 × 96 × 3

# Image Preprocessing

The following preprocessing techniques were applied:
- Image resizing
- Pixel normalization
- Train-test splitting
- Data preparation for CNN training

Pixel values were normalized to the range:
0 to 1


# CNN Architecture

The CNN model includes:
- Convolutional layers
- ReLU activation functions
- MaxPooling layers
- Flatten layer
- Dense layers
- Dropout layer
- Softmax output layer

---

# Model Training and Evaluation

The CNN model was trained using:
- Adam optimizer
- Categorical Crossentropy loss
- Accuracy metric

Evaluation included:
- Training accuracy and loss
- Validation accuracy and loss
- Test accuracy
- Confusion matrix
- Sample predictions

---

# Results

The model achieved strong classification performance on the test dataset.

The confusion matrix showed that most images were classified correctly, with only a few misclassifications between visually similar defect categories.

---

# CNN Concept Explanations

## What is Convolution?
Convolution extracts important visual features from images such as edges, textures, and patterns using filters.

## Why is Pooling Used?
Pooling reduces image dimensions and helps the model focus on the most important features while reducing computation.

## Why is ReLU Commonly Used?
ReLU introduces non-linearity and helps the network learn complex patterns efficiently.

## Why are CNNs Better for Images?
CNNs automatically learn spatial and visual patterns from images, making them more effective than traditional feed-forward neural networks for computer vision tasks.

---

# Business Use Case

This type of computer vision solution can be used in manufacturing industries for automated defect detection.

The system can:
- Detect damaged products
- Improve quality control
- Reduce manual inspection time
- Increase manufacturing efficiency


# Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn
- OpenCV
- Scikit-learn


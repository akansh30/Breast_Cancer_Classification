# Breast Cancer Prediction using Neural Networks

This project implements a neural network model to predict breast cancer diagnosis (malignant or benign) based on various features.

## Dataset

The project utilizes the breast cancer dataset from scikit-learn. This dataset contains features related to tumor characteristics.

## Model

The model is a simple neural network with the following architecture:

- Flatten layer: To convert the input data into a 1D array.
- Dense layer: With 20 neurons and ReLU activation function.
- Dense layer: Output layer with 2 neurons and sigmoid activation function.

## Training

The model is trained using the Adam optimizer and sparse categorical cross-entropy loss function.

## Evaluation

The model's performance is evaluated using accuracy.

## Usage

This project provides a basic example of how to build and train a neural network for classification. It can be used as a starting point for further development and improvement.

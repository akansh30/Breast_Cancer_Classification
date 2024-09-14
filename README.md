# Breast Cancer Prediction using Neural Networks

This project implements a neural network model to predict breast cancer diagnoses (malignant or benign) based on various tumor characteristics.

## Dataset

The project utilizes the breast cancer dataset from scikit-learn. This dataset contains 30 features related to tumor characteristics, including metrics such as radius, texture, perimeter, area, and more.

## Model Architecture

The model is designed as follows:

- **Flatten Layer**: Converts the input data into a 1D array.
- **Dense Layer**: Contains 20 neurons with a ReLU activation function.
- **Output Layer**: Has 2 neurons with a sigmoid activation function to classify the tumor as either malignant or benign.

## Training

The model is trained using:
- **Optimizer**: Adam optimizer
- **Loss Function**: Sparse categorical cross-entropy

## Evaluation

The model's performance is evaluated based on accuracy, achieving approximately 97.7% accuracy on the test set.

## Usage

This project serves as a foundational example of building and training a neural network for binary classification tasks. It can be further developed and improved for more complex applications.

To run the project, ensure you have the required libraries installed and follow the code structure provided in the notebook.

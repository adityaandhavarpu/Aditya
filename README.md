# Machine Learning Assignment - Linear and Logistic Regression Models

This project implements linear and logistic regression models from scratch using gradient descent for predictions based on structured datasets. The aim is to predict housing prices and classify food grain species based on various input features.

## Contents
- Part 1: Linear Regression Model for House Price Prediction
- Part 2: Logistic Regression Model for Food Grain Classification

## Datasets
### For Odd Roll Number Students
- `Boston_House.csv`: Used in the linear regression model for predicting house prices.
- `Pumpkin_Seeds_Dataset.csv`: Used in the logistic regression model for food grain classification.

### Dataset Attributes
Each dataset contains multiple features relevant to the specific prediction task, such as area, perimeter, distance, and other morphological measurements. The target variable in both parts is either numerical (house price) or categorical (grain species).

## Instructions
The project is divided into two main parts:
1. **Linear Regression**:
   - Predict house price using attributes related to housing and location features.
   - Optimized using Batch Gradient Descent.
   - Performance evaluated using Mean Squared Error (MSE).

2. **Logistic Regression**:
   - Classify the species of grain using morphological features.
   - Utilizes the sigmoid function and binary cross-entropy for loss calculation.
   - Performance evaluated using accuracy on test data.

## Implementation Details
- **Linear Regression**:
  - Implemented using Batch Gradient Descent with Mean Squared Error as the loss function.
  - Training process iteratively minimizes the error to produce an optimal model for house price prediction.
  
- **Logistic Regression**:
  - Implements the sigmoid activation function and binary cross-entropy loss.
  - Batch Gradient Descent is used to adjust weights and biases for optimal classification performance.

## Requirements
- Python 3.7+
- Required libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`

## Results
- Linear Regression model is evaluated using MSE on test data.
- Logistic Regression model is evaluated by accuracy score, achieving reliable classification for food grain species.

## Usage
To run the models, open the provided Jupyter notebook, execute each cell in sequence, and evaluate the results based on the performance metrics.

## Acknowledgments
This assignment is intended to demonstrate the fundamentals of linear and logistic regression. Data has been provided to facilitate model implementation and evaluation.

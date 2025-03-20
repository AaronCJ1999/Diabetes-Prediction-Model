# Diabetes-Prediction-Model
This project builds a Machine Learning model to predict diabetes risk based on medical data. Using Python, we preprocess the dataset, train various ML models, evaluate performance, and deploy the best-performing model for real-world predictions.

# Diabetes Prediction Model

This repository contains a Python project that demonstrates how to build a diabetes prediction model using Support Vector Machines (SVM). The code loads a diabetes dataset, preprocesses the data, trains an SVM classifier, evaluates its performance, and makes predictions on new input data.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Code Explanation](#code-explanation)
- [License](#license)

## Overview

The project uses the following steps:
1. **Data Loading:** Reads the dataset from a CSV file using Pandas.
2. **Data Preprocessing:** 
   - Displays basic data statistics and distribution of outcomes.
   - Separates features from the target variable.
   - Standardizes the features using `StandardScaler`.
3. **Data Splitting:** Splits the data into training and testing sets.
4. **Model Training:** Trains an SVM classifier with a linear kernel.
5. **Evaluation:** Computes the accuracy of the model on both training and test data.
6. **Prediction:** Uses the trained model to predict the outcome for a new input sample.

## Dataset

The dataset file, `diabetes.csv`, should be placed in the same directory as the Python script. The CSV file is expected to contain features such as glucose level, blood pressure, etc., along with an `Outcome` column indicating whether a person is diabetic (1) or not (0).

## Requirements

- Python 3.x
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [scikit-learn](https://scikit-learn.org/)

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/AaronCJ1999/Diabetes-Prediction-Model.git
   cd Diabetes-Prediction-Model

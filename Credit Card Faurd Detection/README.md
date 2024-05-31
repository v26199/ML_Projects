# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning models. The goal is to build and evaluate models that can effectively identify fraudulent activities.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction
Credit card fraud detection is a critical task in the financial sector. This project employs machine learning techniques to detect fraudulent transactions from a dataset of credit card transactions. We use Logistic Regression and Random Forest models to classify transactions as either fraudulent or legitimate.

## Dataset
The dataset used for this project contains transactions made by credit cards in September 2013 by European cardholders. It presents transactions that occurred over two days, with 492 frauds out of 284,807 transactions. The dataset is highly imbalanced, with the positive class (frauds) accounting for 0.172% of all transactions.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

## Data Preprocessing
1. **Loading the Data:** Import the dataset and load it into a pandas DataFrame.
2. **Exploratory Data Analysis (EDA):** Analyze the distribution of data, check for missing values, and understand the imbalance in the dataset.
3. **Data Cleaning:** Handle any missing values and perform feature scaling.
4. **Splitting the Data:** Divide the dataset into training and testing sets.

## Modeling
1. **Model Selection:** Choose Logistic Regression and Random Forest as the machine learning models for this task.
2. **Training the Models:** Fit the models on the training data.
3. **Hyperparameter Tuning:** Optimize model parameters for better performance.

## Evaluation
Evaluate the performance of the models using the following metrics:
- Accuracy
- Precision
- Recall
- F1-Score

## Results
- **Logistic Regression:**
  - Training Accuracy: 97.23%
  - Testing Accuracy: 97.26%
  - Precision, Recall, F1-Score: Approximately 97%
    
- **Random Forest:**
  - Training Accuracy: 100.00%
  - Testing Accuracy: 99.98%
  - Precision, Recall, F1-Score: 100%

### The Random Forest model shows slightly better performance but tends to overfit on the training data. 
### The Logistic Regression model provides a balance between simplicity and performance.

## Conclusion
Both models perform well in detecting fraudulent transactions. 
Logistic Regression is preferred for its simplicity and interpretability, while Random Forest offers higher performance but requires careful handling of overfitting.

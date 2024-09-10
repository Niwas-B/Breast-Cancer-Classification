# Breast-Cancer-Classification Using Logistic Regression
This project implements a Logistic Regression model to classify breast cancer cases using the provided dataset (breast_cancer.csv). The model is trained and evaluated using Python libraries such as pandas, numpy, and scikit-learn.

Project Overview
The objective of this project is to predict whether a breast cancer tumor is malignant or benign using logistic regression. The dataset is split into training and test sets, and various evaluation metrics are calculated, including accuracy and cross-validation scores.

Dataset
The dataset used in this project is breast_cancer.csv. It contains several features related to breast cancer tumors and a target column indicating whether the tumor is malignant (1) or benign (0).

Libraries Used
pandas: For data manipulation.
numpy: For numerical operations.
matplotlib: For plotting (if any).
scikit-learn: For machine learning and evaluation.
Steps Involved
Data Loading and Preprocessing:

The dataset is loaded using pandas, and the target and feature columns are separated.
The data is split into training and testing sets using train_test_split.
Model Training:

A logistic regression model is trained on the training set.
Model Evaluation:

Predictions are made on the test set.
A confusion matrix is calculated.
Cross-validation is performed to assess model performance with 10-fold cross-validation.
Model Performance
Accuracy: 96.70%
Standard Deviation: 1.96%

Future Work
Tune hyperparameters to improve model performance.
Experiment with other machine learning models such as Decision Trees or SVMs.

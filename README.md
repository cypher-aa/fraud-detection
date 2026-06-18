# Fraud Detection System

Machine learning pipeline for detecting fraudulent financial transactions using Logistic Regression, SMOTE, and threshold optimization.

## Problem

Financial fraud datasets are highly imbalanced, making traditional accuracy metrics misleading. This project focuses on maximizing fraud detection recall while minimizing costly false negatives.

## Dataset

* 284K+ transactions
* Highly imbalanced dataset
* Fraud rate: ~0.17%

## Features

* Data preprocessing
* SMOTE oversampling
* Feature engineering
* Logistic Regression model
* Threshold optimization
* ROC-AUC and F1 evaluation

## Results

* Accuracy: 97%
* Recall: 89%
* Optimized for fraud detection scenarios

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-Learn
* SMOTE

## Project Workflow

Dataset
↓
Preprocessing
↓
SMOTE
↓
Model Training
↓
Evaluation
↓
Fraud Prediction

## Future Improvements

* XGBoost implementation
* Real-time fraud scoring API
* Model monitoring dashboard

# Financial Fraud Detection using Machine Learning

## Project Overview
This project focuses on detecting fraudulent financial transactions using machine learning models. The dataset contains transaction and identity information, which are processed and used to train classification models.

## Objectives
- Detect fraudulent transactions
- Handle highly imbalanced data
- Compare machine learning models

## Dataset
The dataset contains transaction details and identity information.

Main target variable:
isFraud

## Steps Performed
1. Data preprocessing and merging datasets
2. Handling missing values
3. Label encoding categorical features
4. Handling class imbalance using SMOTE
5. Model training using Random Forest and XGBoost
6. Model evaluation using ROC-AUC and classification report
7. Generating predictions for the test dataset

## Models Used
- Random Forest Classifier
- XGBoost Classifier

## Evaluation Metrics
- ROC-AUC Score
- Precision
- Recall
- F1 Score

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn

## Output
The model generates fraud probability predictions saved as `submission.csv`.

## Author
Shahawaj Pasha

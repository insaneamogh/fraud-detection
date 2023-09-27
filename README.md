# Credit Card Fraud Detection using Machine Learning

This project aims to develop a Credit Card Fraud Detection model using various machine learning algorithms. Credit card fraud detection is a critical problem in the financial industry, where the dataset is often highly imbalanced. In this project, we explore different techniques to handle this imbalance and evaluate the model's performance using precision, F1 score, and accuracy metrics.

## Overview

Credit card fraud is a serious issue, and this project aims to build a machine learning model to detect fraudulent transactions. The project explores different aspects of the machine learning pipeline, including data preprocessing, visualization, modeling, and evaluation.

## Dataset

The dataset used in this project contains credit card transaction data, where fraudulent transactions are highly imbalanced compared to legitimate ones. The dataset has been preprocessed, and features have been scaled using StandardScaler.
https://www.kaggle.com/datasets/arockiaselciaa/creditcardcsv/data

## Preprocessing

Data preprocessing is crucial in preparing the dataset for machine learning. In this project, we:
- Handled missing values (if any).
- Scaled feature values using StandardScaler.
- Addressed class imbalance by applying oversampling and undersampling techniques.

## Exploratory Data Analysis (EDA)

Exploratory Data Analysis is essential to gain insights into the dataset. We visualized the data using Seaborn to understand its distribution, relationships, and identify potential patterns related to fraudulent transactions.

## Modeling

We employed several machine learning algorithms, including:
- Logistic Regression on unbalanced data.
- Random Forest on undersampled and oversampled data.
- Decision Tree on undersampled and oversampled data.
- SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset.

Each model was trained and tuned to optimize performance, with the aim of accurately detecting fraudulent transactions.

## Evaluation

Model performance was evaluated using various metrics:
- Precision: The ability of the model to correctly identify fraudulent transactions.
- F1 Score: The balance between precision and recall.
- Accuracy: The overall accuracy of the model in classifying transactions.

The evaluation results provide insights into how well the model can identify credit card fraud.


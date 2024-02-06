# CodeClauseIntenship_FraudDectection

## Fraud Detection using Decision Tree Classifier

This project focuses on detecting fraudulent credit card transactions using a Decision Tree Classifier. The dataset used contains credit card transactions made by European cardholders, where each transaction is labeled as either fraudulent or valid.

### Dataset Description

The dataset used in this project contains credit card transactions made by European cardholders in September 2013. It consists of features obtained through PCA transformation due to privacy concerns. The target variable 'Class' indicates whether a transaction is fraudulent (1) or valid (0).

### Dataset Source

The dataset used in this project is available on Kaggle and can be downloaded from [this link](https://www.kaggle.com/mlg-ulb/creditcardfraud/download)
.

### Features:

#### Time: Time elapsed in seconds between the current transaction and the first transaction in the dataset
#### V1-V28: Principal components obtained through PCA transformation to protect sensitive information
#### Amount: Transaction amount
#### Class: Target variable indicating whether the transaction is fraudulent (1) or valid (0)

## Project Overview

### Data Exploration:

The dataset is explored to understand its shape, summary statistics, and the distribution of fraudulent and valid transactions.
### Data Preprocessing:

The dataset is preprocessed to prepare it for model training, including splitting it into features (X) and the target variable (Y).

### Model Development:

A Decision Tree Classifier is trained on the preprocessed data to detect fraudulent transactions.

### Model Evaluation:

The trained model is evaluated using various metrics, including accuracy, precision, recall, F1-score, and Matthews correlation coefficient.

## Model Performance

### The trained Decision Tree Classifier achieved the following performance metrics on the test data:

Accuracy: 99.92%
Precision: 75.96%
Recall: 80.61%
F1-Score: 78.22%
Matthews Correlation Coefficient: 0.78

### Conclusion

The Decision Tree Classifier shows promising results in detecting fraudulent credit card transactions. Further optimization and fine-tuning of the model may improve its performance. Additionally, exploring techniques to address the class imbalance in the dataset could enhance the model's robustness.

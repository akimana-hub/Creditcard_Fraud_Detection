# Creditcard_Fraud_Detection
Credit Card Fraud Detection Using Machine Learning
Overview

Credit card fraud is a growing issue worldwide, causing billions of dollars in losses annually. Machine learning can help identify suspicious patterns in transactions and flag potential fraud. This project focuses on developing machine learning models to detect fraudulent credit card transactions using historical transaction data.

Project Motivation

The number of credit card users has increased drastically over the past decade, along with a sharp rise in fraudulent activities. Identity theft and unauthorized use of existing accounts are among the most common types of credit card fraud. With such incidents growing year after year, this project aims to address the problem analytically by applying machine learning methods to classify transactions as fraudulent or legitimate.

Project Goals

Detect fraudulent credit card transactions so customers are not wrongly charged.

Implement and compare multiple machine learning techniques to find the most effective model.

Evaluate each model’s performance using appropriate metrics and visualizations.

Review prior literature and explore different approaches for fraud detection.

Data Source

The dataset used was sourced from Kaggle.com, containing transactions made by European credit card users over two days in 2013. It consists of 284,808 rows and 31 attributes.

28 attributes are anonymized numeric variables transformed using PCA to protect confidentiality.

Time indicates the seconds elapsed between each transaction.

Amount records the transaction amount.

Class is the target variable (1 = Fraudulent, 0 = Non-Fraudulent).

Algorithms Used

This project applies and compares the following machine learning models:

Logistic Regression

Support Vector Machine (SVM)

Decision Tree

Future Work

Potential improvements include testing the model on larger and more diverse datasets, experimenting with different data-splitting ratios, and incorporating external data sources (e.g., geolocation) to enhance fraud detection. For instance, comparing the cardholder’s location with the transaction location could improve the model’s ability to flag suspicious activity.

Conclusion

The project’s primary objective was to identify the most suitable model for credit card fraud detection among the implemented techniques. By evaluating Logistic Regression, SVM, and Decision Tree models, the project highlights their respective performances and potential for real-world fraud prevention applications.

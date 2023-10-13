# Customer-Churn-Prediction
This repository contains a machine learning project aimed at predicting customer churn based on sample telecom dataset.

## Dataset:

The dataset used in this project is taken from Kaggle.

https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data

The data set includes information about:

 • Customers who left within the last month – the column is called Churn

 • Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming     TV and movies.

 • Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges.

 • Demographic info about customers – gender, age range, and if they have partners and dependents

## Exploratory Data Analysis:

Performed thorough data analysis to gain insights into the data, identify patterns, and understand the factors influencing customer churn.

Based on EDA most likely churners are ones with:

  1. Month-to-month contract
  2. Electronic check(payment method)
  3. No online security, no tech support and fibre optics internet
  4. No online backup, no device protection
  5. Non-senior citizens
  6. Those without partner/dependents
  7. In case of people without partner, females are more likely to churn

## Model Building

The dataset is highly imbalanced, so upsampled it using SMOTEENN to achieve better perfomance.

• Experimented with various machine learning models, including decision trees, random forests, logistic regression,naive bayes, gradient boosting, and KNN.

• Metrics like accuracy, precision, recall, and F1-score to evaluate the model's performance.

• Hyperparameter tuning and techniques such as cross-validation were used to optimize model performance.

## Results

**Accuracies:**

Linear Regression: 94.57

Decision Tree   : 94.74

Random Forest   : 93.72

Adaboost        : 94.74

Naive Bayes     : 90.24

KNN             : 95.25

# Customer Churn Prediction

This project addresses the problem of predicting customer churn using a publicly available Churn Dataset. The main goal is to identify the key factors behind customer churn for business institutions. By leveraging predictive models, businesses can benefit from early warnings about customers' churn probabilities, enabling them to take proactive measures to retain valuable customers.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Models](#models)
4. [Results](#results)
5. [Usage](#usage)
6. [Dependencies](#dependencies)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction
Customer churn prediction is crucial for business institutions to maintain and enhance customer relationships. This project aims to develop and compare various machine learning models to predict customer churn and identify significant factors contributing to churn.

## Dataset
The dataset used in this project is the publicly available Churn Dataset. It includes various features related to customer demographics, account information, and usage patterns.

## Models
Several machine learning models were implemented and evaluated in this project:
- **Random Forest**
- **Bagging**
- **Gradient Boosting**
- **Support Vector Machines (SVM)**
  - SVM Linear
  - SVM Polynomial
  - SVM RBF
- **Logistic Regression**
- **Linear Discriminant Analysis (LDA)**
- **Quadratic Discriminant Analysis (QDA)**
- **Naive Bayes**

## Results
The performance of each model was evaluated based on the following metrics:
- Accuracy
- Precision
- Recall
- F1-score
- AUC-ROC

The table below summarizes the results:

| Model               | Accuracy | Precision | Recall | F1-score | AUC-ROC |
|---------------------|----------|-----------|--------|----------|---------|
| Random Forest       | 0.87     | 0.72      | 0.43   | 0.54     | 0.83    |
| Bagging             | 0.83     | 0.75      | 0.08   | 0.15     | 0.78    |
| Gradient Boosting   | 0.86     | 0.71      | 0.42   | 0.53     | 0.84    |
| SVM Linear          | 0.82     | 0.73      | 0.02   | 0.05     | 0.78    |
| SVM Polynomial      | 0.82     | 0.68      | 0.02   | 0.03     | 0.75    |
| SVM RBF             | 0.82     | 0.74      | 0.04   | 0.07     | 0.79    |
| Logistic Regression | 0.83     | 0.77      | 0.08   | 0.15     | 0.78    |
| LDA                 | 0.82     | 0.62      | 0.02   | 0.04     | 0.70    |
| QDA                 | 0.82     | 0.50      | 0.08   | 0.13     | 0.70    |
| Naive Bayes         | 0.81     | 0.41      | 0.04   | 0.07     | 0.58    |

## Usage
To run this project, follow these steps:




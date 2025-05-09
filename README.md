
# Module 20 Report

## Overview of the Analysis

The purpose of this analysis was to develop a machine learning model capable of predicting the risk level of credit loans. The dataset included financial information such as loan size, interest rate, and income, and the goal was to classify whether each loan was high risk (`1`) or healthy (`0`).

Key points from the dataset and analysis:
- The target variable was binary: `0` for healthy loans and `1` for high-risk loans.
- There was a significant class imbalance, with far more healthy loans than high-risk loans.
- The machine learning pipeline involved:
  - Data preprocessing and standardization.
  - Splitting the data into training and test sets.
  - Training a logistic regression model.
  - Evaluating model performance using classification metrics.

## Results

* **Logistic Regression Model**:
  * Accuracy: **99%**
  * Precision:
    * Healthy loans (`0`): **1.00**
    * High-risk loans (`1`): **0.87**
  * Recall:
    * Healthy loans (`0`): **1.00**
    * High-risk loans (`1`): **0.95**
  * F1-score:
    * Healthy loans (`0`): **1.00**
    * High-risk loans (`1`): **0.91**

## Summary

The logistic regression model performed very well overall, with 99% accuracy. It perfectly predicted healthy loans and had strong performance on high-risk loans, despite some class imbalance. The model is likely a strong candidate for practical use in identifying risky credit applications due to the high accuracy rates. Even with slightly lower performance on the high-risk loans, this would still be a very good model for predicting loan risk. 

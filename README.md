# Module 12 Report

## Overview of the Analysis

The purpose of this analysis was to evaluate the performance of different machine learning models in predicting loan risk, distinguishing between `0` (healthy loans) and `1` (high-risk loans). The dataset contained financial information related to loan applicants, and the goal was to predict whether a loan was at high risk based on various features.

To achieve this, we conducted several steps in the machine learning process, including data preprocessing, feature selection, model training, and evaluation. The primary algorithm used in this analysis was `LogisticRegression`. We examined key classification metrics such as accuracy, precision, recall, and F1-score to determine the effectiveness of the model.

## Results

* **Machine Learning Model: Logistic Regression**
    * Accuracy: 99%
    * Precision: 100% (for class `0`), 84% (for class `1`)
    * Recall: 99% (for class `0`), 94% (for class `1`)
    * F1-Score: 100% (for class `0`), 89% (for class `1`)

## Summary

The Logistic Regression model performed exceptionally well, achieving an overall accuracy of 99%. It demonstrated perfect precision for predicting healthy loans (`0`), meaning it rarely misclassified a loan as high-risk when it wasn’t. Additionally, it showed strong recall for high-risk loans (`1`), correctly identifying 94% of them. 

Given these results, I recommend using the Logistic Regression model for loan risk prediction. It balances high accuracy with strong recall, ensuring that high-risk loans are identified effectively while minimizing false positives. If further improvements are needed, techniques such as adjusting class weights or using additional models could be explored.



The development of this project was supported through Instructor Office Hours, class recordings, and tutoring sessions. These resources were instrumental in clarifying concepts, troubleshooting issues, and developing accurate code.

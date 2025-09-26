# Project Title

HR Department Random Forest & Regression Classifier

## Brief One Line Summary

Data science project to predict employee attrition and optimize HR decision-making using logistic regression and random forest algorithms.

## Overview

This project demonstrates how data science can help reduce employee turnover and transform HR processes, leveraging predictive analytics to identify employees at risk of leaving the organization.

## Problem Statement

Recruitment and attrition are costly; this project aims to forecast which employees are likely to resign, helping organizations minimize turnover-related losses.

## Dataset

- IBM HR Analytics Employee Attrition Dataset from Kaggle.
- Sample features: JobInvolvement, Education, JobSatisfaction, PerformanceRating, RelationshipSatisfaction, WorkLifeBalance.
- [Dataset link](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset).

## Tools and Technologies

- Python, Pandas for data manipulation
- scikit-learn for model building (logistic regression, random forest)
- Matplotlib & Seaborn for data visualization
- Colab Notebook for development environment[2][3]

## Methods

- Logistic Regression and Random Forest for classification
- Sigmoid function to calculate probabilities
- Exploratory Data Analysis with KDE plots, box plots, and count plots
- Categorical variable conversion to dummy variables
- Train-test split using scikit-learn
- Artificial Neural Networks (optional extension)[2][3]

## Key Insights

- Classification models can identify employees prone to leaving.
- Precision, Recall, and F1-score are used for model evaluation instead of just accuracy, especially for imbalanced datasets.
- Visualizations can reveal key HR patterns and trends

## Dashboard/Model/Output

- Python scripts and notebooks generate confusion matrix and classification reports
- Model outputs include probability scores for attrition and feature importances.

## How to Run This Project?

To open any notebook from this repository directly in Google Colab:

Copy the notebook's GitHub URL.

Replace github.com with githubtocolab.com in the URL.

Paste the modified URL into your browser and press Enter; the notebook will open in Colab, ready to execute
## Results & Conclusion

- Models achieve improved identification of potential attrition.
- Random Forests provide interpretable feature importances.
- Evaluation metrics (confusion matrix, F1-score) underscore reliability for HR actions.


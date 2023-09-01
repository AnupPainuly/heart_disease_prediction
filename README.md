# Heart Disease Classification

![Heart Image](/home/darkstar/Pictures/heart-disease-pred.jpg)

## Overview

This project focuses on classifying heart disease based on various medical attributes such as age, sex, chest pain type, blood pressure, cholesterol level, and more. We have explored several machine learning models to predict the presence or absence of heart disease, including Decision Trees, Random Forest, XGBoost, and Logistic Regression.

## Dataset

We used the "processed.cleveland.data" dataset, which contains information on patients' health attributes and whether they have heart disease or not. The dataset includes features like age, sex, chest pain type, and more. Missing values and data cleaning were performed to prepare the dataset for modeling.

## Exploratory Data Analysis (EDA)

We conducted exploratory data analysis to gain insights into the dataset. This included visualizations such as count plots, distribution plots, correlation matrices, and pair plots. These visualizations helped us understand the relationships between various features and their impact on heart disease.

## Model Building and Evaluation

### Decision Tree Classifier

We started with a base Decision Tree model and visualized the tree structure. We also pruned the tree using Cost Complexity Pruning and cross-validation to improve its accuracy.

### Random Forest Classifier

We employed Random Forest with hyperparameter tuning to enhance predictive performance. We visualized feature importances to understand which attributes are most influential.

### XGBoost Classifier

XGBoost was used with RandomizedSearchCV for hyperparameter tuning. We evaluated its performance and visualized the ROC curve.

### Logistic Regression

Logistic Regression was another model considered, and we used GridSearchCV to optimize hyperparameters. The ROC curve and accuracy were assessed.

## Results

Here are the results of our model evaluations in terms of accuracy and AUC (Area Under the Curve):

- Base Decision Tree: Accuracy - 0.76, AUC - 0.7024
- Decision Tree with Cost Complexity Pruning: Accuracy - 0.82, AUC - 0.9098
- Random Forest: Accuracy - 0.91, AUC - 0.9776
- XGBoost: Accuracy - 0.9067, AUC - 0.9639
- Logistic Regression: Accuracy - 0.89, AUC - 0.9683

## Conclusion

Based on our analysis, the Random Forest model performed the best in terms of accuracy and AUC, making it a strong candidate for predicting heart disease.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required libraries and dependencies.
3. Run the Jupyter Notebook or Python scripts to explore the dataset and train the models.


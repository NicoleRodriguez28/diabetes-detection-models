# Predicting the Risk of Diabetes with Machine Learning
## Overview
This project uses machine learning to build and evaluate models that predict the likelihood of an individual having diabetes based on clinical, demographic, and physiological data. Using a dataset from [Kaggle](https://www.kaggle.com/datasets/ehababoelnaga/diabetes-dataset/data), this analysis explores key health indicators and applies Logistic Regression, Random Forest, and Support Vector Machine (SVM) to classify diabetes outcomes.
The goal is to identify patterns in patient data that signal diabetes risk and evaluate model performance to determine the most accurate and reliable approach for future predictive health modeling.

## Why It Matters
Diabetes is a major global health concern, and early detection can significantly improve outcomes and reduce complications. By building accurate predictive models, we can help healthcare professionals in identifying high-risk individuals and making data-informed decisions. This project demonstrates how machine learning can be utilized to support public health and preventive care efforts.

## Key Insights
- **Glucose levels** and **BMI** are the strongest predictors of diabetes in this dataset.
- The **Random Forest model** achieved the highest accuracy (95.68%), outperforming Logistic Regression and SVM in all major performance metrics.
- **Feature engineering**, like creating BMI categories, helped improve model interpretability and performance.
- Removing outliers and assessing multicollinearity (VIF) improved the quality of correlation insights and model accuracy.

## Data
[Kaggle Site](https://www.kaggle.com/datasets/ehababoelnaga/diabetes-dataset/data)

- Dataset: Diabetes
- Files: 
  -	testing.csv
  -	training.csv

## Required Packages
- readr: Read data files
- tidyverse: Data packages
- ggplot2: Data visualization
- car: Statistical analysis
- caret: Data modeling/training/evaluation

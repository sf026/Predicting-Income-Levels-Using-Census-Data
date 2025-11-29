Adult-Income-Prediction-Using-Machine-Learning

This project focuses on predicting whether a person earns >50K or <=50K per year based on demographic and employment-related attributes such as age, education, occupation, marital status, workclass, hours-per-week, etc.
The goal is to build a classification model that helps understand income patterns and make accurate predictions.

Project Overview

Income prediction is a commonly studied problem in data science and is widely used in workforce analytics, marketing, and social research.
By applying machine learning techniques, we can classify individuals into High Income (>50K) or Low Income (<=50K) categories based on their historical data patterns.

Key Steps Included:

Data Loading & Understanding

Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA)

Feature Encoding & Scaling

Model Building

Model Evaluation

Exploratory Data Analysis (EDA)

Checked missing values and handled inconsistent entries (?)

Visualized distributions using histograms & boxplots

Examined correlations using heatmaps

Analyzed relationships between income and categorical features

Identified outliers and treated them

Compared class balance for target variable

Model Building & Evaluation

Several machine learning classification models were trained and tested:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Gradient Boosting Classifier

Evaluation metrics used:

Accuracy Score

Precision, Recall, F1-score

Confusion Matrix

ROC Curve & AUC Score

Output:
The final model predicts whether an individual's income is >50K or <=50K based on demographic attributes. This helps in understanding income distribution trends and supports research or business analytics.

Dataset

Source: https://archive.ics.uci.edu/ml/datasets/adult

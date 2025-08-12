# PRODIGY_DS_03
Bank Marketing Campaign Analysis & Prediction

📌 Project Overview

This project analyzes the Bank Marketing Dataset to understand customer behavior and predict whether a client will subscribe to a term deposit (deposit column) based on various demographic, economic, and campaign-related features.

The dataset is processed and analyzed using Python (Pandas, NumPy, Matplotlib, Seaborn) for data cleaning & visualization, and Decision Tree Classifier from Scikit-learn for prediction.

📂 Dataset

File: bank-additional.csv

Source: UCI Machine Learning Repository (Bank Marketing Dataset)
Target Variable: deposit (Yes/No)
🛠 Technologies Used

Python Libraries:
Pandas, NumPy → Data manipulation
Matplotlib, Seaborn → Data visualization
Scikit-learn → Machine Learning
Google Colab for development

📊 Steps Performed

1. Data Loading & Cleaning
Read dataset using pandas.read_csv with ; delimiter
Renamed target column from y to deposit
Checked for:
Shape, column names, and datatypes
Null values and duplicates
Categorical and numerical features

2. Exploratory Data Analysis (EDA)

Summary statistics for numerical and categorical columns
Histograms for numerical features
Count plots for categorical variables
Boxplots to detect outliers
Correlation heatmap for highly correlated features


3. Data Preprocessing

Removed highly correlated features: emp.var.rate, euribor3m, nr.employed
Label encoding for categorical variables
Train-test split (75% training, 25% testing)


4. Model Building
Decision Tree Classifier:
Criterion: gini and entropy
Tuned max_depth and min_samples_split
Model evaluation using:
Accuracy score
Confusion matrix
Classification report

5. Visualization
Decision tree plots for both gini and entropy models

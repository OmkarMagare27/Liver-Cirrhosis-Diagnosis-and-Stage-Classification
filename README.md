# Liver-Cirrhosis-Diagnosis-and-Stage-Classification

# Project Overview
This project aims to develop machine learning models for diagnosing liver cirrhosis and classifying its stages using clinical and biochemical data. The dataset contains 25,000 patient records with demographic, clinical, and biochemical attributes, and the goal is to predict the severity of liver cirrhosis to assist in clinical decision-making.

The project leverages several machine learning models, including Random Forest, Decision Trees, and Gradient Boosting, to classify the cirrhosis stage from mild to severe, based on attributes such as age, albumin levels, bilirubin, and other liver function indicators.

# Dataset
The dataset used in this project contains the following key features:

Prothrombin: A marker of liver function
Platelets: Count of platelets in blood, indicative of liver function
Albumin: A liver-produced protein, lower levels indicate liver dysfunction
SGOT: Liver enzyme (AST) levels, indicating liver damage
Bilirubin: Blood bilirubin level, indicating liver function
Cholesterol: Blood cholesterol level
Copper: Blood copper level, relevant to liver conditions
Age, Sex, Ascites: Demographic and clinical information
The dataset is structured into three classes, representing different stages of liver cirrhosis:

Stage 1: Mild
Stage 2: Moderate
Stage 3: Severe
Data Link:
Attached csv file.

# Project Goals
Stage Classification: Predict the stage of liver cirrhosis (mild, moderate, severe) based on clinical and biochemical features.
Model Comparison: Compare the performance of several machine learning models to determine the best approach for liver cirrhosis diagnosis.
Feature Importance: Identify the most influential features that contribute to disease progression.

# Technologies Used
Programming Language: Python
Machine Learning Libraries: Scikit-learn, XGBoost, LightGBM
Data Preprocessing: Pandas, NumPy
Visualization: Matplotlib, Seaborn

# Model Architecture
Several models were trained and evaluated:

Random Forest: A robust ensemble method that performed well for multi-class classification.
Decision Tree: A simpler model used for baseline comparison.
Gradient Boosting: An ensemble method known for handling imbalanced datasets.
Voting Classifier: An ensemble approach that combines the predictions of multiple models.


# Model Performance:
Random Forest: Achieved an accuracy of 96% with the highest AUC score of 0.993.
Decision Tree: Achieved an accuracy of 92%.
Gradient Boosting: Achieved an accuracy of 86%, slightly underperforming the other models.
Voting Classifier: Achieved an accuracy of 93%, showing strong performance across all classes.

# Results
Best Model: Random Forest, with an accuracy of 96% and excellent generalization capabilities.
Feature Importance: The most important features were Prothrombin, Platelets, and Albumin, which provide key insights into liver function and disease progression.

# Installation and Usage
Prerequisites:
Python 3.x
Scikit-learn
XGBoost
Pandas, NumPy
Matplotlib, Seaborn

# Contributing
Feel free to fork the repository, create a pull request, or open issues for any improvements or bug fixes!

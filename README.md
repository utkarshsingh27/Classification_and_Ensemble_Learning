# Titanic Survival Classification using Ensemble Learning 

## Overview
This project focuses on solving a binary classification task using the Titanic survival dataset, involving the prediction of passenger survival using key demographic and fare-related features. The project applies multiple classification algorithms and explores ensemble learning to improve prediction accuracy.

## Dataset Description: Titanic Survival Data
The dataset used for this analysis is a subset of the Titanic Survival Dataset, which contains information about the passengers onboard the Titanic. The main objective is to predict whether a passenger survived or not, based on certain features.The dataset used for this analysis is a subset of the Titanic Survival Dataset available on Kaggle.

Features Included:
Pclass — Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
Sex — Gender of the passenger (male or female)
Age — Age of the passenger (in years)
Fare — The amount of money paid for the ticket
Embarked — Port of Embarkation (0 = Cherbourg, 1 = Queenstown, 2 = Southampton)

Target Variable:
Survived — Survival status of the passenger (0 = No, 1 = Yes)

## Project Tasks
Data Preprocessing:
Cleaned missing values, encoded categorical features, and normalized inputs where necessary.

Model Selection:
Trained and validated the following classifiers:
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Decision Tree Classifier

Model Evaluation:
Used validation accuracy and confusion matrix to compare models
Selected the best-performing model based on validation metrics
Reported test accuracy for the selected model

Ensemble Approach:
Combined predictions of all three models using majority voting
Compared ensemble accuracy to individual models

Tools Used
Python (Jupyter Notebook)
Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Key Outcomes
Demonstrated model comparison using validation accuracy
Achieved improved prediction using ensemble classification
Showcased end-to-end classification pipeline from data prep to evaluation

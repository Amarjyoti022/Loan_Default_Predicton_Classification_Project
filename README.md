# Loan_Default_Predicton_Classification_Project
Loan default prediction using historical lending data. Includes data preprocessing, EDA, feature engineering, and implementation of multiple ML models (Logistic Regression, KNN, SVC, Decision Tree, Random Forest, AdaBoost, Gradient Boosting, XGBoost) with performance comparison

## Project Overview – Multiclass Loan Default Prediction
This project focuses on predicting loan default risk across multiple categories (e.g., Fully Paid, Charged Off, Current) using historical borrower and loan data. It is a multiclass classification problem aimed at helping financial institutions make better lending decisions.

## Work Done in This Project
-Data Preprocessing

-Converted term from text ("36 months") to integer (36)

-Converted int_rate from percentage string ("10.65%") to float (10.65)

-Extracted issue_year and issue_month from issue_d

-Removed unnecessary columns (id, irrelevant identifiers)

-Encoded categorical variables into numeric form

-Data Cleaning & Wrangling

-Checked for missing values (none found)

-Standardized numerical columns for distance-based models (KNN, SVC)

-Balanced class distribution using class weights

-Exploratory Data Analysis (EDA)

-Distribution of loan purposes and repayment statuses

-Income range analysis for different default categories

-Correlation heatmaps and feature relationships

-Model Implementation

## Compared multiple classification models:
**Logistic Regression (Multinomial), KNN, SVC, Decision Tree, Random Forest, AdaBoost, Gradient Boosting, XGBoost**

-Evaluated models using Accuracy, Precision, Recall, F1-score, and Confusion Matrix

-Insights & Results

-Identified top-performing models for loan default risk classification

-Provided recommendations for lenders based on model outputs

## Tools & Technologies Used
-Programming Language: Python

-Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost

-Jupyter Notebook for development & visualization

-Machine Learning Techniques: Classification algorithms, Feature engineering, Model evaluation metrics



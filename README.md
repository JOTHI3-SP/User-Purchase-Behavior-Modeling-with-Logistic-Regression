# Purchase Intent Prediction using Logistic Regression

This project implements a Logistic Regression model to predict whether an online shopping session results in a purchase using the **Online Shoppers Intention** dataset.  
The focus is on proper preprocessing, model evaluation, and interpretability of logistic regression in a real-world e-commerce context.

## Objective
Predict customer purchase intent (`Revenue`) based on session behavior and traffic-related features.

## Dataset
- Name: Online Shoppers Intention  
- Source: UCI Machine Learning Repository  
- Type: Binary classification  
- Target: `Revenue` (0 = No Purchase, 1 = Purchase)

## Requirements
- Python 3.8+  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seaborn  

## How to Run
Install dependencies:

pip install -r requirements.txt

## Preprocessing and Model
- Logistic Regression
- Feature scaling using StandardScaler
- One-hot encoding for categorical variables  

## Run
python logistic_regression.py

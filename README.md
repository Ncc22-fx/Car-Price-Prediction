# Car-Price-Prediction
Car Price Prediction Model
## Project Overview

This project focuses on building a machine learning model that predicts vehicle prices based on key car attributes such as brand, model, year, fuel type, transmission type, mileage, engine size, and other relevant features.

The objective of this project is to help car buyers, sellers, dealerships, and automobile marketplaces make more informed pricing decisions by estimating fair market values using historical vehicle data.

## Business Problem

Pricing used cars can be inconsistent due to factors such as:

Mileage differences
Vehicle age
Brand reputation
Fuel type
Transmission type
Engine performance
Market demand

Manual pricing often leads to overpricing or underpricing.

This project solves that problem by applying machine learning techniques to automate price estimation based on historical car data.

## Dataset

The dataset used contains various vehicle attributes including:

Car brand
Model
Manufacturing year
Mileage
Fuel type
Transmission
Engine size
Selling price


# Project Workflow
## 1. Data Collection

Imported vehicle pricing dataset into Jupyter Notebook using Python.

2. Data Cleaning
Removed missing values
Handled duplicates
Corrected inconsistent entries
Treated outliers
3. Exploratory Data Analysis (EDA)

Performed visual analysis to understand:

Price distribution
Brand impact on pricing
Mileage trends
Age vs price depreciation
Correlation between variables
Feature Engineering

Created useful variables such as:

Vehicle age
Price per mileage ratio
Encoded categorical variables
Machine Learning Models Used

The following algorithms were tested:

Linear Regression
Random Forest Regressor
Artificail Neural Network

Model Evaluation

Models were evaluated using:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score

The best-performing model was selected based on prediction accuracy.

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
Project Outcome

The final model successfully predicts car prices with strong accuracy and demonstrates how machine learning can improve decision-making in automotive pricing.

Potential applications include:

Car dealerships
Online car marketplaces
Individual car sellers
Financial institutions offering auto loans
Future Improvements
Deploy model using Flask/Streamlit
Integrate live market pricing data
Build web application for users
Improve accuracy with larger datasets
Author

Nwachukwu Caleb Chigozirim
Business Analyst | Data Analyst | MSc Artificial Intelligence & Data Science



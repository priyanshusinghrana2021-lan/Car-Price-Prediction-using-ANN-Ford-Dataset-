# Ford-Price-Prediction-using-ANN-DL
We used ANN and DL

# Project Overview

This project focuses on predicting the price of cars based on their features using a Deep Learning model (Artificial Neural Network). 
The goal is to build a regression model that can: 
Estimate car prices accurately,
Help buyers/sellers make informed decisions,
Demonstrate how ANN works on structured tabular data.
This is a regression problem (predicting continuous values), unlike your previous loan project (classification).

# Dataset Description
The dataset (ford.csv) contains information about different cars and their specifications.
🔹 Input Features (X)
Typical features include:
Model, 
Year, 
Transmission, 
Mileage, 
Fuel Type, 
Engine Size, 
MPG (miles per gallon), 
Tax

👉 These are a mix of:
Categorical features → Model, Fuel Type, Transmission, 
Numerical features → Mileage, Engine size, etc.

# Target Variable (y)
price → Continuous numeric value (car price)

# Pipeline Used
Raw Data
   ↓
Feature-Target Split (X, y)
   ↓
Encoding (pd.get_dummies)
   ↓
Train-Test Split
   ↓
Feature Scaling (StandardScaler)
   ↓
Artificial Neural Network (ANN)
   ↓
Price Prediction

# Technologies Used
Python, 
Pandas → Data handling, 
Scikit-learn, 
Train-test split, 
StandardScaler, 
TensorFlow / Keras → ANN model, 
Matplotlib → Visualization

# Model Performance
Final r2_score = 90 %, 
Final val_r2_score = 91 %














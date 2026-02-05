# Car Price Prediction using Machine Learning and EDA
End-to-end data science project for predicting used car prices using exploratory data analysis and machine learning regression models.

## Overview
This project focuses on predicting car prices based on multiple features such as brand, year of manufacture, fuel type, transmission, mileage, engine capacity, and ownership details. The notebook implements **exploratory data analysis (EDA)** to understand key price drivers and applies **machine learning regression models** to build a price prediction system.

---

## Objective
- Analyze the factors that influence car prices
- Perform EDA to understand relationships between features and price
- Train regression models to predict car prices
- Evaluate and compare model performance using standard metrics

---

## Dataset Description
- **Dataset Type:** Used car listings  
- **Features include:**
  - Brand / Car Name
  - Year
  - Fuel Type
  - Transmission
  - Owner Type
  - Mileage
  - Engine
  - Max Power
  - Seats
- **Target Variable:** Selling Price

---

## Tools & Technologies
- **Language:** Python  
- **Libraries:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
- **Environment:** Jupyter Notebook

---

## Project Workflow

### 1. Data Loading & Inspection
- Loaded dataset using Pandas
- Checked dataset structure, data types, and missing values
- Reviewed summary statistics

---

### 2. Data Cleaning & Preprocessing
- Removed irrelevant columns
- Handled missing values
- Converted categorical variables using encoding techniques
- Transformed numerical columns where required
- Split dataset into training and testing sets

---

### 3. Exploratory Data Analysis (EDA)
- Analyzed price distribution
- Studied relationship between:
  - Price vs Year
  - Price vs Mileage
  - Price vs Fuel Type
  - Price vs Transmission
- Identified key features influencing car prices

---

### 4. Feature Engineering
- Encoded categorical features (Fuel Type, Transmission, Seller Type, Owner)
- Selected relevant features for modeling

---

### 5. Model Development
Trained multiple regression models:
- Linear Regression
- Random Forest Regressor

---

### 6. Model Evaluation
- Metrics used:
  - R² Score
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
- Compared actual vs predicted prices visually
- Plotted prediction error distribution
- Analyzed feature importance from Random Forest

---

## Key Results
- Random Forest Regressor outperformed Linear Regression
- Non-linear relationships exist between car features and price
- Brand, year, mileage, and engine power strongly influence price
- Ensemble models capture complex patterns better than linear models
pip install -r requirements.txt
jupyter notebook Car_Price_Prediction.ipynb

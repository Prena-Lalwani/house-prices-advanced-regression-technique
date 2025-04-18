# 🏡 House Price Prediction using Linear Regression

This project demonstrates a basic regression pipeline for predicting house prices using the [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/) dataset from Kaggle. We use a simple linear regression model to estimate the sale price of houses based on selected numerical features.

---

## 📊 Dataset

The dataset contains 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa. We focus on a few selected numerical features for simplicity:
- `GrLivArea` (Above ground living area)
- `BedroomAbvGr` (Bedrooms above ground)
- `FullBath` (Full bathrooms)
- `GarageCars` (Garage capacity in car count)
- `TotalBsmtSF` (Total square feet of basement)

---

## 📌 Project Workflow

1. Load training and testing datasets using `pandas`
2. Select relevant numerical features
3. Drop rows with missing values for simplicity
4. Split training data into training and validation sets
5. Train a linear regression model using `scikit-learn`
6. Evaluate model performance using MAE and RMSE
7. Predict on test data and generate a submission CSV

---

## 🧪 Model Performance

- **Mean Absolute Error (MAE)**: `28089.29`
- **Root Mean Squared Error (RMSE)**: `43302.81`

> Note: This is a basic linear regression model without feature engineering or hyperparameter tuning. Advanced techniques (e.g., regularization, handling categorical data, feature scaling, etc.) can greatly improve the performance.

---

## 📂 Project Structure


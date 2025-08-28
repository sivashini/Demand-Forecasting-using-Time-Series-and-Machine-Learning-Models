# Weekly-Sales-Forecasting-using-Time-Series-and-Machine-Learning-Models
This project tackles a demand forecasting problem using real-world retail data from Retail sales dataset. The goal is to predict future product demand based on historical sales data.

## 📌 Overview
This project focuses on **demand forecasting** using real-world retail sales data provided in the dataset:

## Models implemented:
- **Linear Regression** (baseline)
- **ARIMA** (AutoRegressive Integrated Moving Average)
- **XGBoost Regressor** (tree-based machine learning model)

## ⚙️ Features
- Load and preprocess retail sales dataset
- Exploratory Data Analysis (EDA) with visualizations
- Feature engineering (e.g., time-based features like week, month)
- Train models (Linear Regression, ARIMA, XGBoost)
- Evaluate performance using RMSE and MAE
- Forecast demand for future periods

## 🛠️ Tech Stack
- **Python 3.x**
- **Pandas, NumPy** → Data manipulation
- **Matplotlib, Seaborn, Plotly** → Visualization
- **scikit-learn** → Linear Regression, metrics
- **statsmodels** → ARIMA model
- **XGBoost** → Gradient boosting regressor

## 📊 Results

- Linear Regression provides a simple baseline for capturing trends
- ARIMA performs well on sequential autocorrelation patterns
- XGBoost effectively models nonlinear relationships and provides robust forecasts

Evaluation metrics (RMSE, MAE) are reported for all models to compare accuracy.

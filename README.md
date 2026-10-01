# StockPredict-99-Accurate-Trend-Analysis-Engine
StockPredict , An advanced Machine Learning project built to predict next-day stock closing prices with industry-grade accuracy using financial time-series data.
# 🚀 StockPredict: 99% Accurate Trend Analysis Engine

An advanced Machine Learning project built to predict next-day stock closing prices with industry-grade accuracy using financial time-series data.

## 📊 Project Overview
Predicting stock prices is challenging due to market volatility. While complex tree-based models like XGBoost often struggle with data extrapolation in strong upward market trends, this project utilizes an optimized **Linear Regression model with Lag Features** to capture market momentum and linear relationships effectively.

The model achieves an outstanding **99.24% R2 Score**, making it highly reliable for next-day forecasting.

## 📈 Key Features
- **Data Preprocessing & Health Check**: Handled time-series formatting and validated clean, null-free dataset constraints across 4,800+ entries.
- **Feature Engineering**: Built rolling metrics and lag variables (`Prev_Close`) to capture historical momentum.
- **Model Evaluation**: Compared standard XGBoost vs. Linear Regression to address trend extrapolation challenges.

## ⚡ Model Performance

| Metric | Value |
| :--- | :--- |
| **R2 Score (Accuracy)** | **99.24%** 🏆 |
| **Mean Absolute Error (MAE)** | **\$1.59** |
| **Next-Day Forecast Example** | **\$132.45** |

## 🛠️ Tech Stack & Libraries
- **Language**: Python 3.12
- **Libraries**: Pandas, NumPy, Scikit-Learn, Matplotlib, XGBoost
- **Environment**: Kaggle Notebooks / Jupyter

## 🏃 How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn xgboost matplotlib
   ```
3. Open the Jupyter Notebook and execute all cells to train the model and generate next-day predictions.

---
*Developed as part of a high-accuracy financial time-series forecasting study.*

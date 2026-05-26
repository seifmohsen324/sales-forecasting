# 📈 Sales Forecasting System

A Machine Learning project that predicts future sales using historical sales data and time-based patterns. The system applies **regression techniques** and **time series forecasting concepts** to estimate future sales trends and support data-driven business decisions.

---

## 📌 Project Overview

Accurate sales forecasting helps businesses improve inventory management, optimize marketing strategies, and make informed decisions. This project analyzes historical sales records and builds predictive models capable of forecasting future sales performance.

The system focuses on creating meaningful time-based features and using Machine Learning models to identify patterns over time.

---

## 🎯 Objectives

- Predict future sales using historical data
- Create time-based features from date information
- Apply regression techniques for forecasting
- Analyze trends and seasonal behavior
- Compare actual vs predicted sales
- Improve forecasting accuracy

---

## 🧰 Technologies & Libraries

<div align="left">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

</div>

---

## 📂 Dataset

Dataset used:

**Walmart Sales Forecast Dataset (Kaggle)**

The dataset contains historical sales information including:

- Store information
- Date
- Weekly sales
- Holidays
- Economic indicators
- Temperature
- Fuel prices
- Seasonal factors

---

## ⚙️ Project Workflow

### 1. Data Collection
- Load Walmart sales dataset
- Explore sales trends and patterns

### 2. Data Preprocessing
- Handle missing values
- Convert date columns
- Clean and organize data

### 3. Feature Engineering

Create time-based features such as:

- Day
- Month
- Year
- Week number
- Lag values
- Rolling averages

These features help the model understand time behavior.

---

## 🤖 Models Used

### Linear Regression
- Simple baseline forecasting model
- Easy interpretation

### Decision Tree Regressor
- Learns non-linear relationships

### Random Forest Regressor
- Improves prediction performance

Bonus experimentation:

- XGBoost
- LightGBM

---

## 📊 Evaluation Metrics

Forecasting models are evaluated using:

- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- R² Score

Visual evaluation:

- Actual vs Predicted sales plots
- Trend comparison over time

---

## 🔍 Covered Concepts

- Time Series Forecasting
- Regression
- Feature Engineering
- Lag Features
- Rolling Averages
- Seasonal Analysis
- Model Evaluation

---

## ⭐ Bonus Features

### Seasonal Decomposition

Break down time series into:

- Trend
- Seasonality
- Residual components

---

### Time-Aware Validation

Instead of random train-test splitting:

- Preserve chronological order
- Prevent data leakage
- Simulate real-world forecasting

---

## 🚀 How to Run

Clone repository:

```bash
git clone https://github.com/yourusername/sales-forecasting-system.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run notebook:

```bash
jupyter notebook
```

or:

```bash
python main.py
```

---

## 📁 Project Structure

```bash
Sales-Forecasting-System/
│
├── dataset/
├── notebooks/
├── src/
├── models/
├── visualizations/
├── main.py
├── requirements.txt
└── README.md
```

---

## 📈 Future Improvements

- Deep learning forecasting using LSTM
- Real-time prediction dashboards
- Deploy using Streamlit
- Hyperparameter optimization
- Add external economic indicators

---

## 📸 Forecasting Pipeline

Dataset → Cleaning → Feature Engineering → Regression Model → Prediction → Evaluation → Forecast Visualization

---

## 👨‍💻 Author

**Saif Fattah**

Computer Engineering Student | AI & Machine Learning Enthusiast

GitHub: https://github.com/seifmohsen324

---

⭐ If you found this project useful, consider giving it a star.

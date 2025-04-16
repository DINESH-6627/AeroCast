# 🏙️ Air Quality Analysis and Forecasting: Jaipur & Kolkata (2018–2023)

This project focuses on analyzing and forecasting the **Air Quality Index (AQI)** of **Jaipur** and **Kolkata** using historical data from **2018 to 2023**. The project involves statistical analysis, visual exploration, time-series modeling, and forecasting using both classical and machine learning methods.

---

## 📌 Objectives

- Understand AQI and its national significance in India.
- Collect and preprocess AQI data (hourly) for Jaipur and Kolkata.
- Perform **descriptive analysis** and **visualizations** to explore patterns.
- Identify **probability distributions** of AQI over different times of the day.
- Decompose AQI time series to understand **trend**, **seasonality**, and **residuals**.
- Apply models like **AR**, **MA**, **ARMA**, **ARIMA**, and **SARIMA** to forecast AQI.
- Explore **statistical learning approaches** for improved predictions.
- Validate and evaluate model performance.

---

## 📥 Data Source

Data is collected from:

- Central Pollution Control Board (CPCB):  
  🔗 [https://airquality.cpcb.gov.in/](https://airquality.cpcb.gov.in/ccr/#/caaqm-dashboard-all/caaqm-landing/aqi-repository)
- AQI standards and calculator:  
  🔗 [https://cpcb.nic.in/National-Air-Quality-Index/](https://cpcb.nic.in/National-Air-Quality-Index/)

---

## 📊 Methods and Techniques Used

### 📌 Exploratory Data Analysis (EDA)
- Time-series plots
- Box plots and violin plots (hourly, daily, monthly AQI)
- Descriptive statistics (mean, std, skewness, kurtosis)
- Distribution fitting (Normal, Gamma, Exponential, etc.)

### 📈 Time-Series Analysis
- Stationarity check using **ADF test**
- Decomposition into **Trend + Seasonality + Residual**
- Autocorrelation (ACF) and Partial Autocorrelation (PACF)

### 🔁 Forecasting Models
- **AR (Autoregressive)**
- **MA (Moving Average)**
- **ARMA (Autoregressive Moving Average)**
- **ARIMA (Autoregressive Integrated Moving Average)**
- **SARIMA (Seasonal ARIMA)**

### 🤖 Statistical Learning Models (Optional/Bonus)
- Linear Regression / Ridge / Lasso
- Random Forest / Gradient Boosting
- XGBoost or LSTM for deep learning

---

## 🔍 Validation & Evaluation

- Train-test split (e.g., last 6 months as test)
- Evaluation metrics:
  - RMSE (Root Mean Square Error)
  - MAE (Mean Absolute Error)
  - MAPE (Mean Absolute Percentage Error)
- Rolling forecast origin (walk-forward validation)

---


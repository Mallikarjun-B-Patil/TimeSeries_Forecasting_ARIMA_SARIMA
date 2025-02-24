# 📊 Time Series Forecasting with ARIMA & SARIMA  

## 📌 Project Overview  
This project focuses on **Time Series Forecasting** using **ARIMA** and **SARIMA** models:  
- **Temperature Dataset:** ARIMA model to analyze trends and forecast future temperatures. 🌡️  
- **Yahoo Stock Dataset:** ARIMA-SARIMA models for stock price prediction. 💹  

## 📂 Dataset Details  
1. **Temperature Dataset**: Contains historical temperature data used for trend analysis and forecasting.  
2. **Yahoo Stock Dataset**: Includes stock prices over time to predict future trends using ARIMA and SARIMA.  

## 🔧 Methodology  
### 1️⃣ Data Preprocessing  
- Handled missing values and outliers  
- Checked for stationarity using **ADF test**  
- Differenced the data if necessary  

### 2️⃣ Model Selection & Training  
- **ARIMA (AutoRegressive Integrated Moving Average)** for Temperature Forecasting  
- **ARIMA & SARIMA (Seasonal ARIMA)** for Yahoo Stock Forecasting  
- Used **ACF & PACF plots** to identify optimal (p, d, q) parameters  

### 3️⃣ Model Evaluation  
- Performance assessed using **MAE, RMSE, and MAPE**  
- Forecasting visualized using **Matplotlib & Seaborn**  

## 📌 Key Findings  
✔ ARIMA successfully modeled temperature trends 📈  
✔ SARIMA improved stock price forecasting by capturing seasonality 🔄  

## 🚀 Technologies Used  
- Python 🐍  
- Pandas & NumPy for data manipulation  
- Matplotlib & Seaborn for visualization  
- Statsmodels for ARIMA & SARIMA modeling  
- Scikit-learn for evaluation metrics  

## 📜 Results & Insights  
- ARIMA effectively forecasts temperature fluctuations.  
- SARIMA enhances stock price prediction by accounting for seasonality.  
- Time series forecasting is crucial for decision-making in finance & climate studies.    

## 🏆 Conclusion  
This project highlights the power of **time series forecasting** in diverse domains. Predicting trends with ARIMA/SARIMA helps in making informed decisions across industries.  

## 📌 How to Run
Clone the repository:
   ```bash
   git clone https://github.com/Mallikarjun-B-Patil/TimeSeries_Forecasting_ARIMA_SARIMA.git
   ```

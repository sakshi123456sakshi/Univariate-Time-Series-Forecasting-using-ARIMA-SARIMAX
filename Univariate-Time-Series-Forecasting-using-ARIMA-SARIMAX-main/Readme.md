# 📈 Univariate Time Series Forecasting using ARIMA & SARIMAX

This project demonstrates how to perform time series forecasting for a grocery store’s monthly sales using classical statistical models like ARIMA and SARIMAX.
The aim is to build a forecasting model that can predict sales for the next 12 months based on historical data.

---

# 🚀 Project Overview
##  Objective

To forecast monthly sales for a grocery store for the next 12 months.

## Techniques Used

Time Series Decomposition

Stationarity Checks (ADF Test)

Differencing

AutoCorrelation (ACF) & Partial AutoCorrelation (PACF)

ARIMA Modeling

SARIMAX Modeling

Forecast Evaluation Metrics


# 📊 Steps Performed
1️⃣ Exploratory Data Analysis

- Visualized the time series.

- Identified trend and seasonality.

2️⃣ Stationarity Check

- Used ADF test to confirm non-stationarity.

- Applied differencing to make the series stationary.

3️⃣ Model Building

- Tried multiple ARIMA (p,d,q) combinations.

- Analyzed ACF & PACF to select model parameters.

- Built ARIMA and SARIMAX models.

4️⃣ Model Evaluation

- Used Metrics

5️⃣ Forecasting

- Final model used to predict future values for the next 12 months.

- Visual comparison of Actual vs Predicted values.

# Project Structure
📦 Time-Series-Forecasting <br>
├── 📄 Time_Series_Forcasting.ipynb <br>
├── 📄 README.md <br>
├── 📄 Img <br>
├── 📄 requirement.txt <br>
└── 📊 dataset.csv   (your dataset if included)

# 🧰 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Statsmodels
- ARIMA & SARIMAX

# 📅 Forecast Output

The model predicts the next 12 months of sales after training on historical data.

# 🏁 Conclusion

This project shows how classical time series forecasting methods like ARIMA & SARIMAX can effectively predict future values for business datasets involving trend and seasonality.
It can be extended to real business forecasting scenarios such as:
- retail sales
- demand planning
- financial forecasting
- production planning

# ⭐ How to Run
- Clone the repository
- Install required libraries
- Open this jupyter notebook (Time_Series_Forcasting.ipynb)
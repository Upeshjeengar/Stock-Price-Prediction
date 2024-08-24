---

# Stock Price Prediction with ARIMA

This project demonstrates time series forecasting of stock prices using the ARIMA model in Python. The ARIMA model is a widely used statistical technique for time series forecasting, which is particularly useful for financial data like stock prices.

## What is ARIMA?

ARIMA stands for Autoregressive Integrated Moving Average. It is a powerful statistical model that predicts future values based on past data. The ARIMA model is characterized by three parameters:

- **p**: The number of lag observations (autoregressive part).
- **d**: The degree of differencing to achieve stationarity.
- **q**: The size of the moving average window.

## Project Overview

In this project, we use historical stock price data to build an ARIMA model to predict future stock prices. The data is collected from Yahoo Finance using the `yfinance` API.

### Steps:

1. **Data Collection**: Fetching historical stock data from Yahoo Finance.
2. **Data Preparation**: Selecting the relevant features (`Date` and `Close` prices).
3. **Data Visualization**: Plotting the historical stock prices.
4. **ARIMA Modeling**: Training the ARIMA model on the prepared data.
5. **Forecasting**: Predicting future stock prices using the ARIMA model.
6. **Model Evaluation**: Assessing the accuracy of the model's predictions.

### Libraries Used:

- `pandas`: For data manipulation and analysis.
- `yfinance`: For downloading historical stock data.
- `matplotlib`: For data visualization.
- `statsmodels`: For ARIMA model implementation.

### How to Run

1. Clone the repository:
   ```sh
   git clone https://github.com/Upeshjeengar/Stock-Price-Prediction.git
   ```
2. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to follow along with the code and results:
   ```sh
   jupyter notebook Stock_Price_Prediction_with_ARIMA.ipynb
   ```
### Customization
You can choose any stock for prediction by updating the _`stock_to_predict`_ variable in the code. This variable is used to specify the stock ticker symbol, which is fetched from Yahoo Finance using the yfinance library.

### 
### Results

The ARIMA model forecasts future stock prices based on past trends. The final section of the notebook demonstrates the predictions and compares them with actual stock prices to evaluate the model's performance.

---

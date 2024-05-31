## ARIMA/SARIMA Stock Price Forecasting

### Overview
This repository contains Python scripts and notebooks for forecasting stock prices using ARIMA (Autoregressive Integrated Moving Average) and SARIMA (Seasonal ARIMA) models. The project aims to analyze and predict the stock prices of the top 100 companies listed in the S&P 100 index, demonstrating how traditional time-series forecasting models can be applied to financial data.

### Features
- **Data Cleaning**: Scripts for handling missing values, infinities, and other anomalies in stock price data.
- **Stationarity Testing**: Implementation of the Dickey-Fuller test to check time series stationarity.
- **Parameter Optimization**: Grid search method to find the optimal parameters for ARIMA/SARIMA models.
- **Forecasting**: Scripts to fit ARIMA and SARIMA models and make future price predictions.
- **Visualization**: Code to visually compare the forecasts against actual historical data.

### Prerequisites
Before running the scripts, ensure you have the following installed:
- Python 3.8+
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Scikit-learn

You can install the necessary libraries using the following command:
```bash
pip install pandas numpy matplotlib statsmodels scikit-learn
```

### Installation
Clone this repository to your local machine using:
```bash
git clone https://github.com/yourusername/stock-price-forecasting.git
cd stock-price-forecasting
```

### Usage
To run the stock forecasting scripts, navigate to the repository folder and execute:
```bash
LTMS.ipynb
```

### Files and Directories
- `data/`: Directory containing CSV files of stock prices.
- `scripts/`: Python scripts for preprocessing, model fitting, and forecasting.
- `notebooks/`: Jupyter notebooks with detailed analysis and model building steps.
- `results/`: Output graphs and model summary results.

### How It Works
1. **Data Cleaning**: The data is cleaned to remove any non-finite values and filled missing entries.
2. **Checking Stationarity**: Each time series is tested for stationarity, and differencing is applied if necessary.
3. **Parameter Tuning**: We use grid search to find the best (p, d, q) parameters for ARIMA models.
4. **Model Building**: ARIMA and SARIMA models are fitted using the optimal parameters found.
5. **Forecasting and Visualization**: The models are used to forecast future stock prices, and results are plotted for evaluation.

### License
Distributed under the MIT License. See `LICENSE` for more information.

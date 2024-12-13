# Stock Prediction Using Facebook Prophet

This project demonstrates a machine learning approach to predict stock prices using Facebook Prophet, a robust time series forecasting model developed by Meta. The notebook showcases how to preprocess stock market data, train the Prophet model, and visualize the results.

## Table of Contents
1. [Introduction](#introduction)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Dataset](#dataset)
6. [Model Overview](#model-overview)
7. [Results](#results)
8. [Acknowledgments](#acknowledgments)
9. [License](#license)

---

## Introduction
Stock market prediction is a challenging task due to its highly volatile nature. This project aims to forecast stock prices using **Facebook Prophet**, which is known for its simplicity and capability to handle missing data, seasonality, and outliers.

## Requirements
The project requires the following Python libraries:
- fbprophet (Prophet)
- yfinance
- pandas
- matplotlib

Additional libraries may be needed for data visualization and handling, such as `plotly`.

## Installation
To set up the environment:
1. Clone this repository:
   ```bash
   git clone https://github.com/RuthOlasupo/stock-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd stock-prediction
   ```
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter notebook file `Stocks_Prediction_FB_Prophet.ipynb`.
2. Install the package to download the financial market data.
3. Preprocess the data (e.g., handle missing values, format timestamps).
4. Train the Prophet model by specifying key parameters.
5. Generate forecasts and visualize the results.

To run the notebook, use:
```bash
jupyter notebook Stocks_Prediction_FB_Prophet.ipynb
```

## Dataset
The dataset used in this project consists of historical stock prices, including open, high, low, close, and volume data. You can use publicly available datasets from platforms like Yahoo Finance or Kaggle.

### Data Columns:
- `Date`: Timestamp of the stock price.
- `Open`: Opening price.
- `High`: Highest price of the day.
- `Low`: Lowest price of the day.
- `Close`: Closing price.
- `Dividends`: Amounts declared in dividends
- `Stock Splits`
- `Volume`: Number of shares traded.

Ensure that the dataset is cleaned and formatted correctly before using it with Prophet.

## Model Overview
Facebook Prophet is a forecasting tool designed to handle time series data effectively. It provides the following features:
- Seasonal decomposition (daily, weekly, yearly trends).
- Inclusion of holidays and special events.
- Robustness to missing data and outliers.

The notebook configures Prophet with parameters to fit stock price data and generate predictions for future timestamps.

## Results
The project produces:
- Forecasted stock prices for the specified time horizon.
- Visualizations of the predicted trends, including components like seasonality and trend decomposition.
- Comparison between historical and predicted prices.

## Acknowledgments
- The **Prophet** library is developed and maintained by Meta.
- Data sourced from [Yahoo Finance](https://finance.yahoo.com) or similar platforms.

## License
This project is licensed under the [MIT License](LICENSE). 

Feel free to contribute, raise issues, or suggest improvements!

--- 

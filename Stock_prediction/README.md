# 2. Stock Price Forecasting Project

## Overview

In this project, I undertake a comprehensive analysis and forecasting of stock prices for five prominent companies: Netflix, Samsung, Starbucks, Microsoft, and Apple. Utilizing a diverse set of machine learning and statistical techniques, I aim to gain insights into historical stock trends and predict future movements. The project involves meticulous data preparation, exploratory data analysis (EDA), and the application of advanced forecasting models such as Prophet, LSTM, and ARIMA.

## Dataset

The dataset, sourced from Kaggle, includes historical stock prices for the following companies:

- **Netflix**
- **Samsung**
- **Starbucks**
- **Microsoft**
- **Apple**

To ensure a consistent analysis across all stocks, the data was merged and filtered to cover a uniform date range from **2002-05-23** to **2024-05-23**. This comprehensive dataset serves as the foundation for my time series forecasting and analysis.

## Analysis and Visualization

### Exploratory Data Analysis (EDA)

We begin with a thorough exploration of the dataset:

- **Line Plots**: Visualized all relevant columns against the date for each stock to understand their temporal behavior.
- **Descriptive Statistics**: Provided summary statistics to highlight key features of the stock prices, such as mean, median, and variance.

### Moving Averages

To identify underlying trends:

- **Daily Average**: Calculated the daily average stock price.
- **Moving Averages**: Computed the 30-day, 50-day, 90-day, and 200-day moving averages to smooth out short-term fluctuations and highlight longer-term trends.

### Trend Analysis

- **Trend Visualization**: Analyzed and visualized the long-term trends of each stock, focusing on the relationship between dates and closing prices.

### Seasonality and Volatility

- **Seasonality Analysis**: Assessed periodic fluctuations in stock prices.
- **Volatility Analysis**: Evaluated price volatility to understand the risk associated with each stock.

### Visualizations

- **Volume vs. Closing Price**: Plotted a scatter plot to explore the relationship between trading volume and closing prices.
- **Distribution of Closing Prices**: Created histograms to visualize the distribution of closing prices, with a specific focus on Netflix.

## Forecasting Models

### Prophet

- **Prophet Forecasting**: Applied the Prophet model to forecast future stock prices for all five companies, capturing trends and seasonal patterns.

### LSTM

- **LSTM Model**: Developed a Long Short-Term Memory (LSTM) neural network to predict stock prices based on historical data.
- **Performance Metrics**: Evaluated model accuracy using Mean Absolute Percentage Error (MAPE):
  - **Netflix**: 0.0850
  - **Microsoft**: 0.0240
  - **Apple**: 0.1290
  - **Starbucks**: 0.0276
  - **Samsung**: 0.0427

### ARIMA

- **ARIMA Forecasting**: Implemented the ARIMA model to provide forecasts and compare with other models' performance.

## Libraries Used

This project leverages a range of powerful libraries to facilitate data manipulation, visualization, and modeling:

- `pandas` for data manipulation
- `numpy` for numerical operations
- `matplotlib` and `seaborn` for data visualization
- `statsmodels` and `scipy` for statistical analysis
- `sklearn` for machine learning utilities
- `prophet` for time series forecasting
- `plotly` for interactive visualizations
- `keras` for building and training the LSTM model

## Conclusion

This project showcases a robust approach to stock price forecasting using advanced statistical and machine learning techniques. By integrating multiple methods and visualizing diverse aspects of stock performance, we gain valuable insights into the behavior of financial markets.

## Running the Project

To run this project, follow these steps:

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/shrutiphutane28/Projects.git
    ```

2. **Navigate to the `Stock_prediction` Folder:**

    ```bash
    cd Projects/Stock_prediction
    ```

3. **Install the Required Dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

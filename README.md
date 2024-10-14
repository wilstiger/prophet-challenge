# Build Your Own Forecasting Model with Prophet

This repository contains a complete implementation of a time series forecasting model using Facebook's Prophet library. The project focuses on analyzing and predicting the popularity of MercadoLibre using Google search traffic data.

## Project Structure

- **Data Analysis**: Investigating patterns in hourly Google search traffic, stock price data, and analyzing seasonality.
- **Stock Price Correlation**: Investigating the relationship between search traffic and stock price volatility and returns.
- **Time Series Forecasting**: Using Prophet to forecast future search traffic based on historical data.

## Steps Implemented:

### 1. Find Unusual Patterns in Hourly Google Search Traffic
- Read and process search data.
- Slice data for specific months.
- Visualize and calculate monthly search traffic patterns.
  
### 2. Mine the Search Traffic Data for Seasonality
- Analyze hourly, daily, and weekly traffic trends.
- Detect time-based trends in search traffic.

### 3. Relate the Search Traffic to Stock Price Patterns
- Concatenate stock price and search data.
- Analyze relationships between search trends and stock volatility.

### 4. Create a Time Series Model with Prophet
- Set up a forecasting model using Prophet.
- Visualize forecasts and individual time series components.

## How to Run the Code

1. Clone the repository.
2. Install the required Python packages:
    ```bash
    pip install pandas matplotlib fbprophet
    ```
3. Open the Jupyter notebook or Python script and execute the cells to see the analysis and forecasting.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Prophet



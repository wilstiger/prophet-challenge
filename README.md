# MercadoLibre Search Traffic Forecasting with Prophet

## Overview
This project analyzes MercadoLibre's Google search traffic and relates it to the company's stock price patterns. The goal is to forecast trends in search traffic and determine whether search traffic patterns can help predict stock market behavior. 

### Key Features:
1. **Hourly Google Search Data**: Analyzing the search data to detect unusual patterns around financial events.
2. **Seasonality Analysis**: Exploring the search data to find seasonality patterns across different hours, days, and weeks.
3. **Stock Price Correlation**: Investigating whether search traffic is linked to MercadoLibre's stock price trends, including volatility and returns.
4. **Time Series Forecasting with Prophet**: Using Facebook's Prophet model to forecast future search traffic trends.

## Structure
- **Find Unusual Patterns in Hourly Google Search Traffic**: Slicing the search data for specific months and identifying patterns that may correlate with financial events.
- **Seasonality Mining**: Grouping search data by time intervals (hours, days, weeks) to identify time-based trends.
- **Relating Search Traffic to Stock Prices**: Combining the search data with stock price data to explore correlations.
- **Time Series Modeling with Prophet**: Forecasting future search trends and analyzing the model's components to understand daily, weekly, and yearly trends.

## Instructions
1. Clone the repository.
2. Install the required dependencies.
3. Run the Jupyter notebook to follow the steps, or use the provided Python scripts for each step of the project.

### Requirements:
- Python 3.x
- Prophet
- pandas
- matplotlib

## License
This project is licensed under the MIT License.

# Scalping Strategy Backtester

## Summary
Using Python, I developed a straightforward yet flexible scalping method. By utilizing the 5-minute timeframe, I was able to maximize trading frequency and improve the risk-reward ratio. Two exponential moving average (EMA) curves are used in this approach to spot trends. 

Long positions are taken during uptrends and short positions are taken during downtrends. 
The Bollinger Bands indicator edges indicate entry points: long positions are entered during an upswing when the price crosses the lower band, while short trades are entered during a downtrend when the price crosses the upper band. At the moment of transaction, the average true range (ATR) is used to set the stop loss.

![Screenshot 2024-04-083085728](https://github.com/sarch25/Simple-Scalping-Strategy/assets/130470960/80dfa682-9f5f-4e0e-a0f5-86efada2e797)

### Skills Learned

- Created a scalping strategy using Python, focusing on adaptability and optimization
- Utilization of technical analysis indicators, such as exponential moving averages and Bollinger Bands, for trend detection and entry points
- Integration of risk management principles, such as setting stop loss based on the average true range
- Application of Python libraries for efficient data analysis, visualization, and strategy development
- Importance of rigorous backtesting and optimization to validate the effectiveness of the trading strategy and ensure robust performance in real-world trading scenarios.

### Tools Used

- Jupyter Notebook: Integrated development environment (IDE) used for coding and experimentation with Python
- Plotly: Library used for interactive data visualization
- Pandas: Python library used for data manipulation and analysis
- Pandas TA: Library for technical analysis indicators integrated with Pandas
- NumPy: Python library used for numerical computing
- Backtesting: This package provides tools and utilities for backtesting trading strategies using historical market data

## Images

#### A section of the Python code defining the logic for generating EMA signals. It includes the creation of a DataFrame for signal tracking, calculations for the current and back candles, and a check to ensure that all EMA fast values remain below the EMA slow values during downtrends. This ensures precise alignment with the strategy's conditions for trend identification.

![Screenshot 2024-04-08 085506](https://github.com/sarch25/Simple-Scalping-Strategy/assets/130470960/7f204e56-92be-4538-8f75-616a7e905e50)
#

#### Backtesting results of the scalping strategy, displaying some key performance metrics such as return percentage, profit factor, win rate, drawdown, sharpe ratio, and the total number of trades, providing an in-depth evaluation of the strategy.
![Screenshot 2024-04-08 085847](https://github.com/sarch25/Simple-Scalping-Strategy/assets/130470960/983c9f30-0370-41d5-adbb-1776ddd5f6e4)
#

#### This chart provides a visual representation of the backtester, featuring candlesticks, upper and lower Bollinger Bands, fast and slow EMAs, and purple dots indicating the exact trade entry points during a trend.

![Screenshot 2024-04-083085728](https://github.com/sarch25/Simple-Scalping-Strategy/assets/130470960/80dfa682-9f5f-4e0e-a0f5-86efada2e797)
#

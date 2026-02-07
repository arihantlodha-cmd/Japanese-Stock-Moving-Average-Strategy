# Japanese Stock Trading Strategy

Algorithmic trading backtester testing moving average crossover strategy on Tokyo Stock Exchange stocks.

## Overview

This project implements and tests a simple moving average (MA) crossover trading strategy on Japanese equities. The strategy generates buy signals when the 50-day MA crosses above the 200-day MA, and sell signals when it crosses below.

## Stocks Tested

- **Toyota Motor Corporation** (7203.T)
- **Sony Group Corporation** (6758.T)
- **SoftBank Group** (9984.T)
- **Nintendo** (7974.T)

## Key Features

- Historical data analysis from 2020-2024
- Buy/sell signal generation
- Performance comparison vs buy-and-hold
- Visualization of strategy performance
- Multi-stock backtesting

## Technologies Used

- **Python 3.x**
- **pandas** - Data manipulation
- **numpy** - Numerical computing
- **matplotlib** - Data visualization
- **yfinance** - Financial data download
- **Jupyter Notebook** - Development environment

## Results

[Add your key finding here after you have the results - e.g., "The strategy achieved varying results across different stocks, with some outperforming buy-and-hold while others underperformed."]

## Files

- `moving-average-strategy.ipynb` - Main backtesting notebook with full analysis

## What I Learned

- Downloading and processing financial market data
- Implementing technical indicators (moving averages)
- Backtesting trading strategies
- Comparing strategy performance against benchmarks
- Data visualization for financial analysis

## Future Improvements

- Add transaction cost modeling
- Test additional MA period combinations
- Implement risk management (stop-loss, position sizing)
- Expand to more stocks and time periods
- Add machine learning predictions

## About

Created by [Your Name] as part of exploring quantitative finance and algorithmic trading. I'm a high school student interested in the intersection of computer science, mathematics, and finance.

## License

This project is for educational purposes only. Not financial advice.
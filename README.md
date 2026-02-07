# 📈 Japanese Stock Trading Strategy

> Algorithmic trading backtester testing moving average crossover strategies on Tokyo Stock Exchange stocks

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Status](https://img.shields.io/badge/Status-Complete-success)

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

The strategy achieved varying results across different stocks, with some outperforming buy-and-hold while others underperformed.

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

Created by Arihant as part of exploring quantitative finance and algorithmic trading. I'm a high school student interested in the intersection of computer science, mathematics, and finance.

## License

This project is for educational purposes only. Not financial advice.

---

## 🚀 How to Run This Project

### Prerequisites
- Python 3.x installed
- Jupyter Notebook

### Installation

1. Clone this repository:
```bash
git clone https://github.com/arihantlodha-cmd/Japanese-Stock-Moving-Average-Strategy.git
```

2. Navigate to the directory:
```bash
cd Japanese-Stock-Moving-Average-Strategy
```

3. Install required packages:
```bash
pip install pandas numpy matplotlib yfinance jupyter
```

4. Launch Jupyter Notebook:
```bash
jupyter notebook
```

5. Open `moving-average-strategy.ipynb` and run all cells

---

## 📸 Sample Output

*Screenshots coming soon - visualizations of trading signals and performance comparison*

---

## 📝 License

MIT License - feel free to use this code for educational purposes.

---

## 🙏 Acknowledgments

- Financial data provided by Yahoo Finance (via yfinance library)
- Inspired by quantitative trading research and my interest in algorithmic decision-making

---

**Questions or suggestions? Feel free to open an issue or reach out!**

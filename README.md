# S&P 500 Prediction with Machine Learning

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

A machine learning pipeline to predict daily S&P 500 movements using Random Forests and technical features.

## Key Features

- **Multi-timeframe feature engineering** (2 to 1000 days)
- **Walk-forward backtesting** to prevent lookahead bias
- **Precision-focused evaluation** for trading strategy development
- **Feature importance analysis** to understand market drivers

## Installation

To follow this project, please install the following locally:

JupyerLab
Python 3.8+
Python packages
pandas
yfinance
scikit-learn
## Data
We use Yahoo Finance's historical market data via the `yfinance` package:

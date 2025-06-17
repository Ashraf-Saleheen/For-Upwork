📈 Crypto SMA Crossover Backtest using Backtrader & PyFolio
This notebook demonstrates a basic Simple Moving Average (SMA) crossover strategy implemented in Python using Backtrader for backtesting and PyFolio for analyzing performance.

🚀 What This Project Includes
Historical BTC-USD data preprocessing (MultiIndex flattening, cleanup)

SMA crossover strategy (SmaCross) using Backtrader

PyFolio integration for performance analysis

Modular code ready for extension into multi-asset or real-time strategies

📦 Libraries Used
backtrader

pandas

matplotlib

empyrical

pyfolio

📊 Strategy Overview
Buy Signal: When short SMA crosses above long SMA
Sell Signal: When short SMA crosses below long SMA

This is a classic momentum-based strategy often used in quantitative trading as a baseline.

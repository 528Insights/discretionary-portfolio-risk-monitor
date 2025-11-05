# discretionary-portfolio-risk-monitor

This project provides a simple discretionary-style portfolio and risk monitoring tool for a small crypto portfolio.  
It tracks live prices, calculates exposure and PnL and simulates a basic hedge to show how partial offsetting of risk improves stability.

# Overview

The notebook uses Python and Yahoo Finance data to:
- Fetch recent hourly prices for BTC, ETH, and SOL  
- Calculate total portfolio value, returns, and daily PnL  
- Measure exposure contributions by asset  
- Simulate a 50% BTC hedge via ETH and compare performance  
- Visualize unhedged vs hedged PnL trends  

The analysis shows how a discretionary trader can monitor and control exposure while keeping directional bias.

# Tech Stack
- Python - Pandas, NumPy, Matplotlib, yFinance
- Runs on Google Colab or any Jupyter environment

# Example Output
- Portfolio value curve  
- Hedged vs unhedged PnL comparison  
- Exposure breakdown by asset  
- Daily PnL summary table  

# Possible Next steps
- Add volatility and Sharpe ratio metrics  
- Integrate additional assets or FX exposure  
- Automate daily reporting to GitHub  
- Connect to exchange APIs for live position data  

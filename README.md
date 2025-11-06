# discretionary-portfolio-risk-monitor

This project provides a simple discretionary-style portfolio and risk monitoring tool that simulates how a discretionary trader tracks portfolio value, exposure, and PnL, and applies partial hedging to stabilize returns.  
The project reflects practical risk awareness and data-driven decision making, both og which are essential skills on a discretionary trading desk.

# Overview

This notebook demonstrates a simple portfolio and risk monitoring process for a small crypto portfolio.  
It uses Python and Yahoo Finance data to:

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

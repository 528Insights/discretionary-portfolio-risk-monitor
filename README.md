This project implements a discretionary-style portfolio and risk monitoring system for a small multi-asset crypto portfolio. The goal is to evaluate how a trader manages exposure, PnL behavior, and hedge effectiveness, rather than relying solely on mechanical entry signals. The emphasis is on understanding how risk moves through the portfolio and how partial hedging can stabilize returns.

Overview

The notebook tracks a portfolio composed of BTC, ETH, and SOL using recent hourly price data. It calculates total portfolio value, asset-level exposure contributions, and simulates a 50% hedge using ETH to offset BTC directional exposure. The system compares hedged and unhedged PnL to illustrate the effect of position-level risk control on return stability.

Approach
	1.	Fetch hourly price data for BTC, ETH, and SOL using yfinance.
	2.	Compute total portfolio value and returns across assets.
	3.	Measure exposure concentration and weight contributions.
	4.	Apply a partial BTC hedge using ETH with a 50% hedge ratio.
	5.	Compare the resulting hedged vs. unhedged PnL curves.
	6.	Visualize exposure dynamics and hedge impact over time.

The workflow mirrors discretionary risk management where exposure is adjusted, not eliminated.

What the System Monitors
	•	Portfolio value evolution
	•	Exposure breakdown across assets
	•	Hedged vs. unhedged PnL behavior
	•	Hedge impact on portfolio variance

Key Insight

The objective is not to remove risk, but to control the amplitude of risk. Maintaining directional bias while smoothing adverse swings leads to more resilient portfolio performance. This reflects real discretionary trading, where judgment and risk sizing matter more than prediction.

Tech Stack
	•	Python (Pandas, NumPy)
	•	yFinance for data acquisition
	•	Matplotlib for visualization
	•	Compatible with Google Colab or any Jupyter environment

Outputs
	•	Portfolio value trend plot
	•	Exposure contribution chart
	•	Hedged vs. unhedged PnL comparison
	•	Hedge effect over time

Next Steps
	•	Add volatility and Sharpe-based performance evaluation
	•	Integrate additional assets or FX exposures
	•	Automate daily reporting to GitHub
	•	Connect to exchange APIs for live monitoring

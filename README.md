# Algorithmic Trading Battle Simulator — Strategy Backtesting Engine


## Developer: Anurag Pratap Singh

An interactive backtesting framework that simulates and compares multiple trading strategies on historical market data. The simulator evaluates strategy performance using key risk and return metrics and visualizes results through animated equity curves.

## Strategies

1. **Momentum Strategy (Moving Average Crossover):**
   - Buys when a short-term moving average crosses above a long-term moving average, sells on the opposite cross.
2. **Mean Reversion Strategy (RSI-based):**
   - Buys when RSI indicates oversold, sells when overbought.
3. **Random Trading Baseline:**
   - Randomly buys or sells at each step, serving as a baseline for comparison.

## Features
- Downloads historical data (default: SPY)
- Modular strategy implementations
- Backtesting with performance metrics:
  - Cumulative returns
  - Sharpe ratio
  - Max drawdown
  - Win rate
- Animated equity curve race with live scoreboard
- Dark theme, smooth transitions, and celebration for the winner

## Tech Stack

- Python  
- Pandas & NumPy  
- Matplotlib  
- yFinance (data retrieval)  
- Modular backtesting architecture


## Usage
1. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the simulator:
   ```bash
   python main.py
   ```


## File Structure
- `main.py`: Entry point, visualization, and animation
- `strategies.py`: Strategy implementations
- `backtester.py`: Backtesting engine and metrics
- `requirements.txt`: Dependencies
- `README.md`: This file

---

*For educational and demonstration purposes only. Not financial advice.*

---
## What I Learned

- Backtesting trading strategies on historical data  
- Risk-adjusted performance metrics (Sharpe ratio, drawdown)  
- Strategy comparison and benchmarking  
- Market behavior modeling  
- Financial data analysis using Python

---

## Future Improvements

- Add transaction costs and slippage modeling  
- Implement reinforcement learning-based trading agent  
- Add portfolio-level multi-asset simulation  
- Integrate live data streaming  
- Deploy as an interactive web dashboard (Streamlit)

---

Made by **Anurag**

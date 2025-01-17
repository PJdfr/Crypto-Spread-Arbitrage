# Crypto-Spread-Arbitrage
This repository contains a project that leverages historical data to design and test an arbitrage strategy between spot cryptocurrencies and their perpetual futures counterparts. The goal is to identify opportunities where the spread between spot prices and perpetual futures prices diverge, allowing for potential arbitrage profits.

## Key Components:
Backtest Notebook: A Jupyter notebook that uses historical data from Kraken to simulate the arbitrage strategy. The notebook includes data analysis, strategy development, and performance metrics to evaluate the effectiveness of the arbitrage model over time.

Live Dashboard: A real-time monitoring dashboard that tracks the spread between spot prices and perpetual futures for various cryptocurrencies. It provides live updates on the market and flags potential arbitrage opportunities based on real-time data pulled from Kraken's API.

## How to Use:
Clone the repository.
Install the required dependencies using pip install -r requirements.txt.
Run the backtest notebook to simulate the arbitrage strategy over historical data.
Launch the live dashboard to monitor real-time spread data and receive alerts for potential arbitrage opportunities.
## Disclaimer:
This project is for educational and research purposes only. Use at your own risk. The performance of any arbitrage strategy in live markets can be affected by a variety of factors, including latency, transaction costs, and market conditions.

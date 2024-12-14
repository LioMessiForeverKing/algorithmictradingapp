# AlgorithimicTrading
Stock Price Forecasting with Monte Carlo Simulation
This project implements a Monte Carlo simulation to forecast stock prices and estimate the probability of a stock price falling below a given strike price over a specified period.

Overview
The script, Forecast.py, simulates potential future stock price movements based on historical data and key statistical parameters. It evaluates the risk of a stock price breaching a defined strike price, which is especially useful in options trading and risk management scenarios.

Key Features
Monte Carlo Simulation: Generates thousands of possible price paths to model future stock price behavior.
Strike Price Analysis: Estimates the probability of the stock price falling below a predefined level.
Visualization: Plots simulated price paths for visual analysis of potential trends.
How It Works
The core functionality resides in the forecast function, which:

Inputs Parameters: Initial stock price, mean daily return, standard deviation, simulation days, number of runs, and strike price.
Simulates Price Movements: Models stock prices over the specified period using random daily returns sampled from a normal distribution.
Tracks Risk Events: Counts how often the stock price drops below the strike price.
Calculates Probability: Outputs the likelihood of breaching the strike price and generates price path data for visualization.
Usage
The simulation is executed with these default parameters:

Initial Price: 41.95
Mean Daily Return: 0.00050814
Standard Deviation: 0.022468102
Simulation Period: 12 days
Runs: 10,000
Strike Price: 36
It outputs:

The probability of the stock price falling below the strike price.
A plot of all simulated price paths.
Applications
This tool is ideal for:

Options Traders: Assessing the likelihood of stock prices hitting strike prices.
Risk Managers: Evaluating potential downside risks.
Quantitative Analysts: Studying the impact of statistical parameters on stock price forecasts.

# Financial Derivatives Pricing
This project involves analyzing historical stock data for META (Facebook) and performing various financial computations to understand and value financial options based on the historical performance of the selected ticker. The project is structured as follows:

# Project Objectives
1. Data Acquisition: Download historical stock data for META from Yahoo Finance in CSV format.
2. Data Visualization: Plot historical stock prices to visualize performance over time.
3. Log-Returns Analysis: Calculate and plot log-returns to analyze returns on a logarithmic scale
4. Statistical Analysis of Log-Returns:
    * Assess whether log-returns are normally distributed using:
    * QQ plots
    * Histograms
    * Statistical tests (Jarque-Bera, Kolmogorov-Smirnov)
5. Volatility Estimation: Estimate historical volatility using log-returns.
6. Risk-Free Rate Identification: Identify the risk-free rate for the USD currency (3-month Treasury rate).
7. Independence Testing: Test the assumption that log-returns are independent and uncorrelated.
8. Option Pricing:
    * Calculate the price of an In-The-Money (ITM) European call option and an In-The-Money European put option with a specific maturity date.
    * Employ various methods for option pricing:
    * CRR (Cox-Ross-Rubinstein)
    * Black-Scholes
    * Simulation Methods
9.Advanced Volatility Estimation: Use advanced methods for volatility estimation such as GARCH or stochastic volatility methods for more accurate option pricing.


# Methodology
* Data Analysis and Visualization: Conducted using Python libraries like pandas, matplotlib, and seaborn.
* Statistical Testing: Performed using statistical tests to validate assumptions about the data.
* Option Pricing Models: Implemented and compared different models to price European options.

# Results
Jupyter Notebook containing:
1. Data analysis and visualizations
2. 2.Statistical tests and results
3. Option pricing computations and comparisons












# Multi-Method-Value-at-Risk-VaR-Modeling-Portfolio-Risk-Analysis
This project implements a comprehensive risk analytics framework to measure and evaluate portfolio downside risk using multiple Value at Risk (VaR) methodologies. It combines historical data analysis, statistical modeling, and simulation techniques to provide a robust understanding of financial risk.

# Objective:

To build a multi-method VaR model that:

Quantifies portfolio downside risk
Compares different VaR approaches
Validates model accuracy using backtesting
Analyzes extreme market conditions through stress testing


# Methodologies Implemented
1. Historical VaR
Uses empirical return distributions
No distribution assumptions
Captures real market behavior

2. Parametric VaR (Variance-Covariance)
Assumes normal distribution of returns
Uses mean and standard deviation
Fast and widely used in finance

3. Monte Carlo Simulation VaR
Simulates 10,000+ return scenarios
Provides forward-looking risk estimation
Captures uncertainty in market movements

4. Expected Shortfall (CVaR)
Measures average loss beyond VaR
Captures tail risk more effectively

5. Rolling VaR
Time-varying risk estimation
Identifies volatility clustering and regime changes

6. Backtesting
Evaluates model accuracy
Compares expected vs actual VaR violations

7. Stress Testing
Simulates extreme market conditions
Tests portfolio resilience under high volatility



# Tech Stack

Python
Pandas – Data manipulation
NumPy – Numerical computations
Matplotlib – Data visualization
SciPy – Statistical modeling
yFinance – Financial data extraction


# Historical price data for:

Reliance Industries
TCS
HDFC Bank
NIFTY 50 Index
Gold ETF

Time Period: 2022 – 2024


# Key Features:

Multi-asset portfolio construction
Multi-method VaR comparison
Tail-risk measurement using CVaR
Model validation via backtesting
Scenario-based stress testing
Visual risk analytics


# Key Insights:

Historical VaR effectively captures fat-tail risk
Parametric VaR may underestimate extreme losses
Monte Carlo simulation provides forward-looking risk scenarios
Rolling VaR highlights time-varying volatility
Diversification reduces overall portfolio risk
Backtesting helps assess model reliability


# How to run the project:

#Install dependencies
pip install yfinance pandas numpy matplotlib scipy

#Run the script
python var_model.py

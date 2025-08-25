# credit-market-risk-basel3
## Overview
This project demonstrates the quantification and aggregation of credit and market risk under Basel III and IFRS 9 standards. It is designed as a portfolio risk analysis, including forward-looking stress testing and scenario analysis.

## Features
- **Credit Risk**: Estimation of Expected Credit Loss (ECL) using the Home Credit Dataset.
- **Market Risk**: Calculation of Value at Risk (VaR), Conditional VaR (CVaR/Expected Shortfall), and rolling volatility.
- **Stress Testing**: Application of macro-level stress indicators using the St. Louis Fed Financial Stress Index (STLFSI) and scenario analysis.
- **Aggregation**: Combined analysis of credit and market risks for total portfolio risk.

## Data Sources
- **Home Credit Dataset** (Kaggle) – for credit risk modeling [download here] (https://www.kaggle.com/c/home-credit-default-risk/data).
- **Yahoo Finance** – for market risk (LQD, TLT, S&P/TSX Composite Index).
- **St. Louis Fed FRED** – for financial stress index.

## Python Libraries
- pandas, numpy
- yfinance, pandas_datareader
- scikit-learn
- matplotlib, seaborn

## Data Preparation
- Missing values are removed or imputed.
- Sampled data is used for modeling where appropriate.
- Synthetic LGD and EAD values are assigned for demonstration purposes.

## Usage
1. Clone the repository.
2. Open the Jupyter Notebook `credit_market_risk_basel3.ipynb`.
3. Install required packages: `pip install -r requirements.txt`.
4. Run the notebook step-by-step to reproduce the analysis.

## Analysis & Results
- **Credit Risk**: Logistic regression used to estimate PD, combined with LGD and EAD to compute ECL by credit rating and sector.
- **Market Risk**: VaR and CVaR computed for portfolio of LQD, TLT, and S&P/TSX; rolling volatility visualized.
- **Stress Testing**: High stress periods identified via STLFSI; stressed ECL and market risk scenarios simulated.
- **Scenario Analysis**: Comparison of baseline and stressed portfolio risk under different stress scenarios.

## Notes
- Stress scenarios and synthetic values are illustrative; real-world application requires calibrated data.
- This project is intended for educational and portfolio presentation purposes.


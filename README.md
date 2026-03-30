# S&P 500 Stocks — 25 Years of Data: Complete Business Analysis

A comprehensive analysis of S&P 500 stock market data spanning 25 years of daily trading records.

## Overview

This project explores the statistical and financial properties of S&P 500 constituent stocks using Python. The analysis covers sector-level risk/return profiles, market volatility patterns, return distributions, Sharpe ratios, inter-stock correlations, and short-term price forecasting.

## Contents

| File | Description |
|------|-------------|
| `sp500_analysis.ipynb` | Main analysis notebook |
| `chart1_sector_risk_return.png` | Sector risk vs. return scatter plot |
| `chart2_market_volatility.png` | Market volatility over time |
| `chart3_return_distribution.png` | Distribution of daily returns |
| `chart4_sharpe_ratio.png` | Sharpe ratio by sector |
| `chart5_correlation_heatmap.png` | Inter-stock correlation heatmap |
| `chart6_forecast_AAPL.png` | Price forecast — AAPL |
| `chart6_forecast_ABBV.png` | Price forecast — ABBV |

## Analysis Sections

1. **Data Understanding** — Loading and exploring the dataset (OHLCV format)
2. **Part 1** — Data cleaning and feature engineering
3. **Sector Risk/Return** — Risk-adjusted performance across S&P 500 sectors
4. **Market Volatility** — Rolling volatility analysis over 25 years
5. **Return Distribution** — Statistical properties of daily returns
6. **Sharpe Ratio** — Risk-adjusted return comparison by sector
7. **Correlation Analysis** — Heatmap of cross-stock correlations
8. **Forecasting** — Linear regression-based short-term price forecasts

## Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
```

Install with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Data

The notebook expects `sp500_stocks.csv` (daily OHLCV data) in the working directory. If the file is absent, a realistic synthetic dataset is generated automatically to mirror the statistical properties of real S&P 500 data.

The dataset can be downloaded from [Kaggle — S&P 500 Stocks](https://www.kaggle.com/datasets/andrewmvd/sp500-stocks).

## Usage

```bash
jupyter notebook sp500_analysis.ipynb
```

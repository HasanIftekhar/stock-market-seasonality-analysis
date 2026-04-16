# Stock Market Seasonality Analysis

**University of Stavanger — Data Mining (DAT200)**

## Overview

Benchmarked 4 forecasting models on seasonal stocks sourced from Yahoo Finance to identify trend and seasonality patterns. Random Forest achieved R² above 0.99 on 3 of 4 stocks; ARIMA outperformed all models on trend capture, while LSTM showed overfitting on limited time-series data.

## Stocks Analyzed

- Apple (AAPL)
- Microsoft (MSFT)
- Disney (DIS)
- Norwegian Air (NWARF)

## Models Compared

| Model | Strengths | Notes |
|-------|-----------|-------|
| Linear Regression | Fast baseline | Misses non-linear patterns |
| ARIMA | Best trend capture | Strong on temporal dependencies |
| Random Forest | **R² > 0.99 on 3/4 stocks** | Best overall performance |
| LSTM | Sequence modeling | Overfitting on limited data |

## Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn (Linear Regression, Random Forest)
- Statsmodels (ARIMA)
- TensorFlow / Keras (LSTM)
- Matplotlib, Seaborn
- Yahoo Finance API (yfinance)
- Jupyter Notebook

## Files

- `G02 Stock Market Analysis.ipynb` — full implementation and model benchmarking
- `data.csv` — preprocessed stock data
- `G02 Stock Market Analysis Finding the Seasonality and Trend.pdf` — project report

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook "G02 Stock Market Analysis.ipynb"
```

# Github-S-P-500-Companies-Forecasting

## Overview
Predicting short-term closing prices for S&P 500 stocks using
historical OHLCV data. This project explores feature engineering,
baseline models, and a Random Forest regressor, evaluated on RMSE.

## Business Question
Can we build a reliable short-term price direction signal
that outperforms a naive baseline?

## Dataset
- Source: Kaggle — S&P 500 Stock Data (Cam Nugent)
- 5 years of daily OHLCV data across 500+ tickers
- ~600,000 rows

## Project Structure
data/           Raw CSV files
notebooks/      Numbered Jupyter notebooks (EDA → modelling)
src/            Reusable Python utilities
outputs/        Saved plots and result CSVs

## Results
*(To be completed — see notebooks/03_modelling.ipynb)*

## Setup
pip install -r requirements.txt
jupyter notebook

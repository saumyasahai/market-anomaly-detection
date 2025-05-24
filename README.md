# Market Behavior Anomaly Detection

This project applies unsupervised machine learning techniques to detect anomalies in stock market trading behavior using time series data (volume, return, volatility).

## Methods Used

- Z-Score filtering
- Isolation Forest (from scikit-learn)
- Feature Engineering (Volatility, Returns)
- Time Series Visualization

## Technologies

- Python (Pandas, Numpy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook

## How It Works

1. Load time series market data
2. Engineer features: log returns, volatility
3. Detect anomalies using Z-Score and Isolation Forest
4. Visualize anomalies on volume and time

## Example Use Case

Detect unusual trading patterns or potential market manipulation in equity markets.

## Getting Started

```bash
pip install -r requirements.txt

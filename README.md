# CVXPY_Stocks

## Portfolio Optimization with Convex Optimization

"_This assignment only covers the fundamental idea and is a component of the course Optimization Theory and Its Applications in Signal Processing and Communications._"

This repository implements Markowitz Mean-Variance Portfolio Optimization using CVXPY to construct efficient portfolios from real stock data. The project demonstrates how convex optimization helps balance risk and return while incorporating practical constraints like no short-selling and sector limits.

### Key Features
✔ Efficient Frontier – Visualize optimal risk-return trade-offs <br />
✔ Real Stock Data – Fetch and analyze historical prices using yfinance <br />
✔ Convex Optimization – Solve portfolio allocation using CVXPY <br />
✔ Constraints Handling – No short-selling and turnover limits <br />
✔ Robust Analysis – Sensitivity to input parameters (μ, Σ) <br />

### Installation
```
git clone https://github.com/Cheer3142/CVXPY_Stocks.git
cd CVXPY_Stocks
```

Fetch Stock Data
```
from data_fetcher import get_stock_data
tickers = ["AAPL", "MSFT", "GOOG", "AMZN"]
data = get_stock_data(tickers, start="2020-01-01", end="2023-12-31")
```




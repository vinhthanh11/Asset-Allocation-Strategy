### Asset Allocation Strategy: Portfolio Performance
This Jupyter notebook provides an analysis framework for asset allocation strategy and portfolio performance evaluation, including efficient frontier estimation. The analysis is performed using historical asset prices fetched from Yahoo Finance, covering various financial metrics and optimization techniques.

### Key Functions and Analysis Steps
## Downloading Asset Prices
The analysis starts by downloading historical prices for a predefined list of assets from Yahoo Finance. Adjust the ASSETS list as needed for your analysis.

## Calculating Simple and Logarithmic Returns
Simple returns are calculated to understand the basic return profile of the assets. Logarithmic returns are then computed to facilitate various statistical analyses and are preferred for mathematical properties beneficial in financial models.

## Normality Tests
Histograms and quantile-quantile plots are generated for logarithmic returns to assess the normality of return distributions. This is crucial for understanding the underlying assumptions of many financial models.

## Annual Metrics Calculation
Annual means, covariances, and correlation matrices of log returns are estimated to provide a basis for portfolio optimization and risk management.

## Correlation Matrix Visualization
A heatmap of the correlation matrix offers insights into the relationships between asset returns, which is essential for diversification and risk assessment.

## Portfolio Weights and Returns
Portfolio weights are defined equally across assets, and portfolio returns are calculated. This serves as a baseline for performance evaluation.

## Basic Portfolio Performance
Quantstats library is used to generate a snapshot of the portfolio's performance, including metrics like Sharpe ratio and maximum drawdown.

## Portfolio Optimization using Monte Carlo Simulation
A Monte Carlo simulation is employed to explore a wide range of random portfolio weights, aiming to identify the efficient frontier by estimating expected returns and volatility.

## Plotting the Efficient Frontier
The efficient frontier is visualized, illustrating the trade-off between portfolio return and risk. This helps in identifying portfolios with the highest return for a given level of risk.

## Contributing
Feel free to fork the repository and submit pull requests to contribute to the development of this analysis framework.

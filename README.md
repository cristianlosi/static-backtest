## Portfolio Backtesting: Sharpe Ratio Optimization vs. Equal Weighting

[cite_start]This project, based on the `Static_Backtest.ipynb` script[cite: 1, 2], implements a static backtesting framework to evaluate the performance of an optimized investment portfolio.

### Methodology

The analysis is structured into two main phases to ensure a robust evaluation of the strategy:

* [cite_start]**Data Splitting**: The dataset is partitioned into an **In-Sample** period, used to calculate the optimal asset weights, and an **Out-of-Sample** period to verify how the portfolio performs with those weights in a real-world scenario[cite: 1, 2].
* [cite_start]**Weight Optimization**: I identified the specific weights that **maximize the Sharpe Ratio**, aiming for the best possible risk-adjusted return[cite: 1, 2].
* [cite_start]**Performance Comparison**: The optimized portfolio's performance is analyzed over a one-year horizon and compared against an **Equally-Weighted (1/N) portfolio** benchmark[cite: 1, 2].

### Key Objectives
* Demonstrate the impact of mean-variance optimization on portfolio returns.
* Validate the stability of optimal weights when applied to unseen data.
* Visualize the performance gap between a naive diversification strategy and a risk-adjusted optimization.

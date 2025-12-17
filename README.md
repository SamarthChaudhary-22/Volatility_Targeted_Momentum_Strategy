# A Risk-Adjusted Momentum Strategy with Volatility Targeting and Transaction Costs in Indian Equities
This project implements a systematic momentum investing framework applied to Indian equities, enhanced with institutional-grade risk controls. Stocks from a predefined Indian equity universe are ranked based on medium-term momentum, and the top performers are selected into a concentrated portfolio.

To improve risk efficiency, portfolio construction uses inverse-volatility weighting rather than naïve equal weighting, ensuring that more volatile stocks receive smaller allocations while lower-risk stocks contribute more evenly to total portfolio risk. The strategy is rebalanced quarterly, explicitly accounting for transaction costs and portfolio turnover to maintain realism.

Performance is evaluated against the Nifty 50 benchmark over a multi-year horizon using comprehensive metrics, including CAGR, volatility, Sharpe and Sortino ratios, maximum drawdown, drawdown duration, hit rate, beta, correlation, and tail-risk measures (VaR and CVaR). Rolling volatility and rolling Sharpe diagnostics are also analyzed to study regime-dependent risk behavior, including stress periods such as the COVID-19 market shock.

Overall, the project demonstrates how combining momentum with volatility scaling and rigorous risk diagnostics can produce a more stable and professionally deployable return-generating strategy in emerging equity markets.

The repository contains personal projects prepared during computational finance self-learning. The projects are being continuously updated.

01_THEORY_OptionPricing_Greeks_ImpVol.ipynb:

Pricing European call and put options on a (continuous) dividend paying stock using the Black-Scholes-Merton (BSM) formula, Fast Fourier Transform (FFT) for the BSM, Heston and Variance Gamma models including model calibration with the BSM prices as a reference, and Monte Carlo simulations. Calculations of selected Greeks and implied volatility using the Newton-Raphson and Brent's methods are also presented.


02_PRACTICE_OptionPricing_Vol_VaR_ES.ipynb:

1. Two stocks data from within one year long time period and options chain load with initial formatting, analysis and visualization.
2. Introduction of the Black-Scholes-Merton (BSM) model for a non-dividend paying stock with determination of its parameters, i.e. the spot price and risk-free interest rate.
3. Volatility smiles for selected Tesla options' expiry dates & volatility surfaces.
4. The BSM option prices for the Tesla stocks using historical volatility - comparison with the YF data.
5. Implied volatility for the Tesla options using the Brent's method - comparison with the YF data.
6. The BSM option prices for the Tesla stocks using the calculated implied volatility - comparison with the YF data.
7. Value at risk and expected shortfall calculations for a two-asset portfolio with the use of the historical, variance-covariance (parametric) and Monte-Carlo methods.


03_PRACTICE_PortfolioOptimization.ipynb:

1. Four stocks data load from within a ten years long time period with initial formatting, analysis and visualization.
2. Construction of the portfolio with initial analysis of its components.
3. Construction of an efficient frontier for the considered portfolio and its mean-variance optimization.
4. Calculation of value at risk and expected shortfall for the optimal portfolio.
5. Stress testing of the optimized portfolio using Monte-Carlo simulations.
6. Mean-variance and maximizing Sharpe ratio portfolio optimizations with a GARCH(1,1)-based 30-day forward-looking volatility forecast.

# Python for Finance Projects

A collection of quantitative finance and risk management models implemented using Python for practical applications in market risk measurement and derivatives pricing.

---

## Projects

## 1. Value at Risk (VaR) Modeling

Developed a multi-asset portfolio risk model using historical market data for:

- SPY
- Apple (AAPL)
- Tesla (TSLA)
- Amazon (AMZN)
- Microsoft (MSFT)

Implemented and compared three major Value at Risk methodologies:

### Methods Used
- Historical Simulation VaR
- Parametric (Variance-Covariance) VaR
- Monte Carlo Simulation VaR

### Key Features
- Portfolio return and volatility estimation
- Risk measurement at 90%, 95%, and 99% confidence levels
- Monte Carlo scenario generation using random normal sampling
- Comparative analysis of different VaR methodologies
- Visualization of risk estimates across methods

### Concepts Applied
- Market Risk Modelling
- Statistical Modeling
- Portfolio Return Analysis
- Risk Visualization

---

## 2. Options Pricing & Implied Volatility Models

Implemented analytical and numerical pricing models for European call options and analyzed convergence behavior between discrete-time(Binomial Model) and continuous-time(Black-Scholes) pricing models when number of time steps increases.

### Models Implemented
- Black-Scholes Option Pricing Model
- Two-Step Binomial Tree Model
- Multi-Step Binomial Pricing Model
- Implied Volatility Estimation using Numerical Root Solving (`fsolve`)

### Key Features
- Comparison between Black-Scholes and Binomial model outputs
- Analysis of convergence of Binomial pricing toward Black-Scholes with increasing tree steps
- Numerical estimation of implied volatility from market option prices
- Application of risk-neutral valuation concepts

### Concepts Applied
- Derivatives Pricing
- Implied Volatility
- Numerical Methods
- Risk-Neutral Valuation
- Numerical Root Solving
---

## Tools & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- SciPy
- yFinance
- datetime

---

## Background

These projects were developed as part of practical learning in quantitative finance and financial risk management using Python.

---

## Author

**Saksham Agarwal**

Actuarial Science and FRM student with interests in:
- Quantitative Finance
- Market Risk Modelling
- Derivatives Pricing
- Financial Modeling

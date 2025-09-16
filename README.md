# Monte Carlo Simulation: Stock Portfolio & Option Pricing

This project implements a Monte Carlo simulation for:

1. Stock portfolio value evolution
2. Portfolio Value-at-Risk (VaR) and Conditional Value-at-Risk (CVaR)
3. European call option pricing

It provides insights into portfolio risk metrics and option valuation using Python.

---

## Table of Contents

* [Overview](#overview)
* [Features](#features)
* [Requirements](#requirements)
* [Usage](#usage)
* [Project Structure](#project-structure)
* [License](#license)

---

## Overview

This project simulates the daily evolution of a stock portfolio using historical stock data from Yahoo Finance. It calculates:

* **Monte Carlo simulations** for portfolio values
* **Value-at-Risk (VaR)** at a 5% confidence level
* **Conditional Value-at-Risk (CVaR)** at a 5% confidence level

Additionally, the project performs **Monte Carlo simulation for European call option pricing**, estimating the theoretical option value, standard error, and comparing it to market value.

---

## Features

* Fetches historical stock data using `yfinance`
* Computes daily returns and covariance matrix
* Runs Monte Carlo simulations for stock portfolios
* Calculates portfolio VaR and CVaR
* Monte Carlo-based European call option pricing
* Graphical visualization of portfolio evolution and option price distribution

---

## Requirements

* Python 3.9+
* Libraries:

  * `numpy`
  * `pandas`
  * `matplotlib`
  * `scipy`
  * `yfinance`
  * `pandas_datareader`

Install dependencies using:

```bash
pip install numpy pandas matplotlib scipy yfinance pandas_datareader
```

---

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/monte-carlo-portfolio.git
cd monte-carlo-portfolio
```

2. Run the main script:

```bash
python monte_carlo_portfolio.py
```

3. Outputs:

* Portfolio evolution plot over time
* Monte Carlo simulated portfolio VaR and CVaR
* European call option pricing with probability distribution and comparison to market price

---

## Project Structure

```
monte-carlo-portfolio/
│
├─ monte_carlo_portfolio.py   # Main Python script
├─ README.md                  # Project documentation
└─ requirements.txt           # Optional: list of dependencies
```

---


## References

* Yahoo Finance API (`yfinance`)
* Monte Carlo Methods for Financial Simulation
* Python for Finance, Yves Hilpisch

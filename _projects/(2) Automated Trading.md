---
name: Automated Trading
tools: [Data Visualization, Time Series, Pandas-Datareader]
image: https://images.unsplash.com/photo-1535320903710-d993d3d77d29?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1740&q=80
description: Automatically buys or sells stock based on the short and long running averages.
---

# Automated Trading System


### Project Overview

This **Automated Trading Analysis**, developed as part of my academic journey in CUS690 - Applied Analytics, showcases my hands-on approach to stock trading strategy optimization using historical data. The project leverages the `pandas_datareader` API, and contains a `StockTrader` class for trading individual stock data and `PortfolioTrader` for managing multiple stocks within a portfolio. The progtam explores the fine-tuning of `short_moving_average` and `long_moving_average` values for a specified stock portfolio. This project allowed me to gain insights into basic trading strategy principles while practicing my data analysis and python development skills.

### Strategy and Implementation

At its core, the `PortfolioTrader` class conducts a grid search for each stock's optimal `short_moving_average` and `long_moving_average` parameters within user-defined ranges, aiming to maximize returns over a trading period.

The trading strategy can be summarized as:

- **Sell**: `short_moving_average` crosses below `long_moving_average`
- **Buy**: `short_moving_average` crosses above `long_moving_average` (after a sell)
- **Buy More**: `short_moving_average` consistently stays above `long_moving_average`

The project's focus is on maximizing returns by optimizing parameter values. Performance assessment includes logarithmic and arithmetic returns.

#### Trading Results and Analysis

| Citigroup Stock Example | Disney Stock Example |
|-----|-----|
| ![C Stock Example](/assets/img/AutomatedTradingSystemC.png) | ![DIS Stock Example](/assets/img/AutomatedTradingSystemDIS.png) |


More details and examples can be found on my github, below.


---

<p class="text-center">
{% include elements/button.html link="https://github.com/petertadrous/automated-trading" text="Learn More" %}
</p>

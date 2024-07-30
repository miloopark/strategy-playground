# Strategy Playground

Playing around with the implementation of various trading strategies using Python. Each strategy is presented in a Jupyter notebook, providing step-by-step instructions and explanations.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Implemented Strategies](#implemented-strategies)
  - [Dual Class Arbitrage](#dual-class-arbitrage)
  - [Bollinger Band Strategy](#bollinger-band-strategy)
  - [Reinforcement Learning Algorithm](#reinforcement-learning-algorithm)
  - [Sector-Based Pairs Trading Algorithm](#sector-based-pairs-trading-algorithm)
- [Dependencies](#dependencies)

## Introduction

This project aims to implement and backtest various trading strategies using historical stock data. The strategies covered include:
- Dual Class Arbitrage
- Bollinger Band Strategy
- Reinforcement Learning Algorithm
- Sector-Based Pairs Trading Algorithm

Each strategy is implemented in a separate Jupyter notebook, providing a clear and interactive way to understand and analyze the performance of each strategy.

## Getting Started

To get started, clone the repository and install the necessary dependencies.

```sh
git clone https://github.com/yourusername/trading-strategies.git
cd trading-strategies
pip install -r requirements.txt

```

## Implemented Strategies

Dual Class Arbitrage
This strategy involves taking advantage of the price discrepancy that exists between stocks that have dual listings (e.g., GOOG vs GOOGL).

Notebook: Dual_Class_Arbitrage.ipynb

Bollinger Band Strategy
Bollinger bands are calculated by taking the 20-day simple moving average (SMA) of a stock price and then calculating the upper and lower bounds as the SMA ± two standard deviations of the actual stock price.

Notebook: Bollinger_Band_Strategy.ipynb

Reinforcement Learning Algorithm
Reinforcement learning is leveraged in various applications for algorithmic trading. This strategy involves building an RL algorithm to trade a particular financial product.

Notebook: Reinforcement_Learning_Trading.ipynb

Sector-Based Pairs Trading Algorithm
This strategy is based on the premise that two assets within the same sector/industry will likely have similar performances. Significant deviations in their prices can be capitalized on by buying the falling asset or shorting the rising asset.

Notebook: Sector_Based_Pairs_Trading.ipynb

## Dependencies
The project requires the following Python libraries:

numpy
pandas
matplotlib
yfinance
statsmodels
scikit-learn
tensorflow (for Reinforcement Learning Algorithm)

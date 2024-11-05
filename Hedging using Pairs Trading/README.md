# Hedging with Pairs Trading

This project implements a **Pairs Trading Strategy** for risk-managed, market-neutral investing. Using correlated asset pairs, it takes simultaneous long and short positions to profit from temporary mispricings, regardless of overall market direction. The strategy shows resilience and stable returns, even in bearish market conditions.

## Project Overview

Pairs trading is a quantitative strategy designed to exploit price relationships between two historically correlated assets. By going long on the "undervalued" asset and short on the "overvalued" asset, the strategy aims to profit from mean reversion while minimizing exposure to market-wide risk.

In this project, I developed a pairs trading model that:
- Identifies suitable asset pairs
- Executes trades based on price divergence
- Uses statistical measures to assess risk and return
- Shows robust performance even during market downturns, proving it to be an effective hedging strategy

## Key Features

- **Market Neutrality**: The long-short structure reduces exposure to overall market trends.
- **Risk Management**: Metrics like Sharpe Ratio, Sortino Ratio, and Maximum Drawdown are used to manage and monitor risk effectively.
- **Bear Market Resilience**: The strategy generated positive returns even in the current bear market, highlighting its potential as a hedge.

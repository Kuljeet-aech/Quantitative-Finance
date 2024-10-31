# Backtesting Options Straddle Trading Strategy

This project Backtests an options straddle trading strategy with defined stop-loss and profit-target rules. The strategy combines selling an at-the-money (ATM) straddle and hedging the position with out-of-the-money (OTM) options to limit downside risk.

## Strategy Overview
1. **Sell ATM Straddle**: Sell both an ATM call and an ATM put option with the same strike price and expiration date at the start of the trading day.
2. **Purchase Protective OTM Wings**: Buy an OTM call and an OTM put option, each with a strike price 3% above and below the ATM strike, respectively, for risk mitigation.
3. **Set Stop Loss and Target**: Define a stop-loss threshold at 30% of the premium collected from the ATM straddle and a profit target at 100% of the premium collected.
4. **Monitor and Exit Conditions**: Continuously monitor the trade. Exit all positions when either the stop-loss or profit target is reached, or close all positions at the end of the trading day if neither condition is met.

## Files
1. **main.ipynb**: Jupyter Notebook containing all the python implementation of the backtesting procedue with visulizations
2. **Trade Report.xlsx**: Excel explaining how the trades were executed throughout the trading time period.

However, the option prices data cannot be shared because of copyright issues.

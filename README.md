# first_trading_strategy
Implementation and testing of a trading bot
## Description
[BTC_USD_210101_220101.csv](https://github.com/solver322/first_trading_strategy/blob/main/BTC_USD_210101_220101.csv) - BTC-USD pair history prices

[trading_bot.ipynb](https://github.com/solver322/first_trading_strategy/blob/main/trading_bot.ipynb) - strategy implementation and testing
## Strategy
The bot trades on a pair of BTC-USD on 5-minute intervals. It finds a local minimum/maximum and, subject to additional conditions, opens a long/short position. Exit the trade either by stop loss or ladder taking profit


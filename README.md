# Summary
This Jupyter notebook is consist of Pairs Trading in FAANG stocks, Event Driven Backtesting and Evaluation

## Pairs Trading in FAANG stocks

- Cointegration test is chosen for finding the correlated pairs for this pairs trading strategy, and I choose 7% as minimum P-value for the cointegration test, heatmap & OLS result are also used for analysis.
- I concluded the below criteria for pairs trading in this project by plotting and analysing spread between real data and regression result of NFLX stock price
>if 20 days' rolling normalized spread > +3, short NFLX/META pair, i.e. short sell NFLX and buy META, both using 50% of the total capital <br>
> <br>
>if 20 days' rolling normalized spread < -3, long NFLX/META pair, i.e. buy NFLX and short sell META, both using 50% of the total capital <br>
> <br>
>if 20 days' rolling normalized spread is between -3 and +3, hold the current portfolio.

## Event Driven Backtesting

An Event Driven Backtesting library backtrader is used for backtesting, the back-tester with documentation in the coding, using the criteria for pairs trading mentioned above is included the notebook with below assumptions
- time horizon is 4 years from 2018 to 2022
- starting cash is $10000
- trading commission fee is 0.5%

## Evaluation

- A portfolio analysis library pyfolio is used for evaluating the backtesting result with different metrics
- Backtrader's built-in function is also used for presenting a snapshot of the trades throughout the time horizon

## Related Project
[Crypto Pairs Trading and Event Driven Backtesting](https://github.com/Hansen-chen/Crypto_Pairs-Trading-and-Event-Driven-Backtesting)


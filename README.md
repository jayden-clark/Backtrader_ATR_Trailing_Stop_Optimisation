# Backtrader_ATR_Trailing_Stop_Optimisation
This strategy features the ATR Trailing Stop indicator that I created. The strategy uses ES E-mini S&P 500 Futures data from 2020 and involves a buy signal when the ATR Trailing Stop line crosses above the close price and a sell signal when it crosses below. The strategy also features Backtrader's bracket-order mechanism which is useful for software like Interactive Brokers's Trader Work Station. The bracket order features a target (or take-profit) and a stop, both of which are parameters that are being optimized.

In this case, the optimisation is coded to ensure that only parameters that make a profit over the time perid (ie. ending value > $10 000 000) are found.

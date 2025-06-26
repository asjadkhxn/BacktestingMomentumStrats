Backtesting Period: 2010-01-01 to Present

Used a 12-month lookback period (T = 12) & a 1-month skip period (S = 1).

Also, used raw cumulative return as a metric to rank stocks, coded in an option to use the risk-adjusted returns as well!

Contents:

Part1: 100% Momentum (contains survivorship bias)
       - Used NIFTY50, NIFTY100, NIFTY200 & NIFTY500 as investible universes.
       - Created 16 Portfolios (Changing holding period, H = [1,3,6,12] months)

Part2: Addressing Survivorship Bias
       - Used NIFTY50 and its past constituents as the investible universe.
       - Created 4 Portfolios (Changing holding period, H = [1,3,6,12] months)
       - Compared these to their NIFTY50 100% Momentum (Sur Bias) counterparts.
       - Noticed fall in Sharpe, and increase in max drawdowns.

Part3: Value + Momentum
       - Combined value and momentum factors. 
       - Approach not emphasized but included for completeness.

Ignored trading and custody costs and any taxes.
----->  "With the growth of strong discount brokers in India, general
 	investors are able to execute trades at low or no brokerage fees. India has a range of small charges
 	including taxes (Securities Transaction Tax 0.1% on purchase and sale and Goods and Service Tax
 	at 18% on brokerage and transaction charges), transaction charges by the stock exchanges, SEBI
 	Turnover Charges (0.00015% of the transaction value) and some taxes levied by state governments.
 	These costs are slightly in excess of 0.1 bps per leg." - Rajan Raju 

Used Equal Weighting throughout the assignment.
----->  Each firm has the same weight, w = 1/N.


THANK YOU!

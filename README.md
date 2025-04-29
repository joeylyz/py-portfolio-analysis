# Portfolio performance/risk analysis

a very simple but real life portfolio analysis tool
start portfolio construction with long and short equity
step by step calculation of daily/monthly return, culmulative return  vs benchmark
analysis on key metrics including sharp, VaR
factor analysis using FF model

### step 1: construct a Long Short portfolio
for simplicity, pick US stock only (yfinance data avaible), vanilla cash stock only

### step 2: calculate daily return of stock, daily/cumulative return of the portfolio
a sanity check to see if there is any outliners on price information we retrived from yfinance

### step 3: calculate monthly return of the portfolio
to see how porfolio monthly performance

### step 4: calculate gross and net exposure of porfolio
leverage of portfolio, and whether the exposure is positive or negative

### step 5: calculate common ratio
annualized return, annualized volatility, maxium dradown, sharpe ratio, sortino ratio

### step 6: factor analysis
factor analysis using fama french 3 factor.
Barra risk would be more ideal and practical, unfortunately need data access
chart the coeffecient (i.e. how the model explained) and the residuals (how reliable the result is)

### step 7 :portfolio risk
calculate standard deviation, value at risk, and CVaR
plot for return distribution
plot rolling shape ratio and rolling maximum drawdown

### step 8: sector exposure
calculate sector exposure of portfolio

### step 9: top PnL contributor










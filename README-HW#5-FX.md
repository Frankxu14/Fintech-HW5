# Homework Unit 5 - Financial Planning
# Frank XU

## Summary
In this Homework, I access most recent crypto and share trading prices via API (Alternative API and Alpaca API).
Assuming a retirement investment portfolio comprised of cryptos (BTC and ETH) and shares, I calculate and advise client on if their liquidation cash value will be sufficient as emergency fund.

With Alcapa API the code fetches most recent 3 years of trading data, and run 30 Year and 5 Year Monte Carlo simulations, on a portfolio allocation/weight distribution of 40/60 between SPY (S&P 500) and AGG (Bonds). With Matplotlib it plots the charts for 30 Year and 5 Year MC simulation of cumulative returns, probability distribution, and statistic summary.

Based on assumed initial investment amounts, I calculate and print the range of Monte Carlo simulated portfolio returns at 95% confidence level.






## Additional Note:
### 1. As the "load_dotenv()get_env function" cannot work locally, I hard-coded Alpaca API Key and Alpaca Secret Key, but comment them out for homework submission.
### 2. The cryptos, SPY and AGG shares prices are most up to date. For Monte Carlo simulation, I also use the most recent 3 years trading prices as input.
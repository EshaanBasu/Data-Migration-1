# Data-Migration-1
Data Migration Preparation Project

We will start with an empty folder with a list of 30 stock tickers, with no data/database. By the end we will have a github repo where one command (python run_all.py) does the following from scratch:
  1. Download 2 years o real prices, splits, and dividends.
  2. Generate 2 years of trades for 5 fake accounts
  3. Rebuilds daily positions, cash, and account value from those trades in SQL
  4. Create Custodian copy of the data in a different format with about 15 planted errors
  5.  Reconciles my data against the custodian's and outputs a break report
  6.  the break report is the final output

Core Migration loop:
  1. Take someone else's data in their format and map it to mine
  2. load it, prove it matches

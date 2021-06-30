# F743_scrapy_project

### instruction to run
scrapy crawl mostactive -o -file_name.csv

### this project pulls daily stock data from https://finance.yahoo.com/most-active/ to get the most active 25 stocks and save items/data points include
stock_name, intraday_price, price_change, current_timestamp, prev_close, open_price, bid,
ask, range_day, range_52weeks, volume, volume_avg, market_cap, beta_5yr_monthly,pe_ratio, eps,
earnings_date, fwd_div_yield, exp_div_date, est_yr_target 

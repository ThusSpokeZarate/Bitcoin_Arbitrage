# Bitcoin_Arbitrage
Analyzing historical Bitcoin price data for arbitrage opportunities

1. Collect the data

> For this analysis we are utilizing data from two popular cryptocurrency exchanges, Bitstamp and Coinbase.  Specifically, we are looking at the price of bitcoin (BTC) in Q1 2018.  The data is initally imported into unedited data frames and requires further prepartion before proceeding with analysis. 

2. Prepare the data

>The data needs to have any objects converted to floats within the dataframes.  The data then needs to be sliced to focus on the closing prices on each exchange.  If there are any arbitrage opportunities, they will be identified by comparing the closing price of BTC over different time frames.

3. Analyze the data

> Here we are looking at the difference in closing prices, to see when the difference can provide a return greater than the 0 and greater than the 1% fee required to make trades between the two exchanges.  From here we can also visualize the price differences over time to decide of there is any pattern over time that can be exploited for profitable trades.
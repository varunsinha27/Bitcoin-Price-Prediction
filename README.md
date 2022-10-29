# Bitcoin-Price-Prediction

Bitcoin was among the first cryptocurrencies developed in 2009 as anonymous Satoshi 
Nakamoto. With no requirement for a central clearinghouse or trustworthy record-keeping authority, 
Bitcoin acts as a decentralised medium of digital exchange. Transactions are validated and recorded in 
a public distributed ledger (the blockchain) without the use of a middleman. However, ever since its 
existence, there always have been some issues with bitcoins like high volatility of BTC and long
transaction delays. The high volatility of Bitcoin has been a problem in predicting the price of BTC 
which creates a problem for financial investors. It has been observed that the price of Bitcoin has
fluctuated quite rapidly with outside influential factors such as tweets from Elon Musk, war, natural 
disasters, or any government decision or changes.
We have used the dataset extracted from Coinbase, which is the most widely used 
cryptocurrency exchange platform across the whole world. Dataset is publicly accessible without any 
requirement of APIs or any other secured function. We have chosen the data of Bitcoin prices from 
2014 – 12 – 01 to 2018 – 11 – 11 when there used to be a lot of fluctuation in the BTC prices with the 
boom in the cryptocurrency market. The dataset consisted of 1,048,576 entries and 8 features. The 
dataset entries for OHLC (Open, High, Low, Close) have been updated from minute to minute. Open 
(opening price on that day), close (closing price on that day), high (highest on a particular day), low 
(lowest on a particular day), and volume (total quantity of Bitcoin traded). Weighted price (average of 
the price during the day), and volume (currency) (total volume of currencies traded) were the features 
available in the dataset to perform the analysis.
In the following sections, we will analyse the historical dataset of Bitcoin prices by performing 
some visual analytics techniques to perform exploratory data analysis to get insight from it and then 
build forecasting machine learning models like LSTM, ARIMA, and XGBoost to predict the price of 
Bitcoin and visually analyse the performance of all the three models followed by a comparison of metric 
scores and price prediction curve of all three whether the model was able to predict the price accurately. 

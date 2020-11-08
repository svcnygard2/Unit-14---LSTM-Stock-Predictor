# Unit-14---LSTM-Stock-Predictor
Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the Crypto Fear and Greed Index (FNG) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency.
## In this assignment:
- I will use deep learning recurrent neural networks to model bitcoin closing prices. 
- I will have one model  use the FNG indicators to predict the closing price while the second model will use a window of closing prices to predict the nth closing price.
## Performance Evaluation:
- Which model has a lower loss?
The model with the lowest loss was the with the Bitcoin closing prices data (0.0444).
- Which model tracks the actual values better over time?
The closing price model tracks actual values better over time.  The plot shows that well and the variance in the closing compared to the FNG is better (10-Day Closing Variance - 2140; 10-Day FNG Variance - 5325).
- Which window size works best for the model?
The window size that worked best for the model was the 5-day window because the variance is 1976 whereas the the variance in a 10-day window is 2140.
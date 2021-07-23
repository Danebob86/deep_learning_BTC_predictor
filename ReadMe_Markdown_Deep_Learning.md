# Unit 14 - LSTM Stock Predictor

![Credit card fraudster](https://www.zdnet.com/a/hub/i/r/2018/04/13/36c52953-7ab9-4608-a848-71d1d538856e/resize/1200x900/cb25970cc96ac118c177e2f67690763b/td-deep-learning.jpg)

## Background
Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the Crypto Fear and Greed Index (FNG) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency. You have been asked to help build and evaluate deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.

# Summary

## Questions
* Which model has a lower loss?
    * The closing price model has a lower loss at 0.05 vs. 0.08 for FNG model. 
* Which model tracks the actual values better over time?
    * The FNG model predcits actual values better over time. 
* Which window size works best for the model?
    * In my models a higher window size works better. For purposes of the subject homework, I left it the widnow size at 10. 
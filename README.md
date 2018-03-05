# Stock Price Prediction<br />
**The project was done for a financial trading company. The goal of it was to predict the stock price as accurate as possible.**<br /><br />
The data set contains daily stock closed price in history.  
Three models that have a statisfied prediction performance:
1. Linear regression with feature selection
2. Xgboost
3. Time series ARMA

Judged by the new data set, the time series ARMA model outperforms the others. To improve the prediction performance, I use the one-step forward prediction strategy, which means every time it's used for prediction, it needs to be trained by the lastest data set, so it takes the most computational cost. But that's fine if it's not for high-frequency trading.

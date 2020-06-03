The project is  Portfolio Optimization with Validation Using Time Series Forecasting and Deep Learning.

Firstly, we use Markowitz Model, which is a portfolio optimization model which assists in the selection of most efficient portfolio by analyzing various possible portfolios for the given stocks or securities.
For example - If you have 1 lakh available to invest in some stocks, the model tells you how much you should invest in each stock. 

Here we have considered 3 stocks for analysis - 

1] ICICI Bank (ICICI.BO)

2] Hindustan Unilever Ltd (HINDUNILVR.BO)

3] Larsen & Toubro (LT.BO)


The bracket contains the ticker symbol (how the stock is represented on the stock exchange, in this case the Bombay Stock Exchange as indicated by BO)

Then we have used 3 different models to predict the stock price - 

1] Moving Average 

2] Long Short Term Memory (LSTM)

3] Auto Regressive Integrated Moving Average (ARIMA)


The model which has the least Root Mean Square Error, is used to predict on future prices so that we can validate that the prediction made by the Markowitz Model is appropriate.

# ARIMA-Model-Time-Series-Stock-Forecasting
Python Portfolio Exercise

Load the dataset TLSA stock close price 2014-2024
![](Image/LoadDf.png)<br>
<br>
Time series forecasting is a method used to predict future values based on previously observed values in a time-ordered sequence (for example Stock prices)<br>
In this project, the focus would be on the ARIMA model and how it can be used to make stock prices prediction<br>
### ARIMA
**AutoRegressive (AR) part:**  uses the stock's past prices to predict its future prices. This assumes that past prices have a linear relationship with future prices.<br>
**Integrated (I) part:** The 'Integrated' part addresses this by differencing the stock price series to remove trends and achieve stationarity.<br>
**Moving Average (MA) Component:**  This involves modeling the error term as a linear combination of error terms occurring contemporaneously and at various times in the past. The MA component captures the relationship between an observation and a residual error from a moving average model applied to lagged observations.<br>

### Check for Stationarity

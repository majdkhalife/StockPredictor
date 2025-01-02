## Welcome to My Stock Predictor GitHub Page!
Here, I’m experimenting with various models to predict stock prices and sharing my implementations along with what I've learnt from the process. If you're interested in exploring how data can be used to model the stock market, this repository is a great place to start.

As a student, I’ll update this repo as time permits, and I appreciate any feedback or contributions!

As of right now, I have implemented 3 different models:
ARIMA, GARCH and LSTM, each of which have model independent scenarios.

## ARIMA<br>
Its main purpose is that it forecasts future values of a time series based on past values and errors.<br>
Key Characteristics:<br>
  -Useful for data with trends or seasonal patterns.
  -Relies on differencing to make the time series stationary.
Strengths:<br>
  -Well-established and easy to interpret.
  -Good for univariate forecasting (one stock at a time).
Limitations:<br>
  -Assumes linearity in the data.
  -Can struggle with abrupt market changes or highly volatile time series.

## GARCH:<br>
Its main purpose is that it models and forecasts the volatility (variance) of returns over time.<br>
Key Characteristics:<br>
  -Focuses on changing variance (volatility clustering) rather than the mean.
  -Useful when large price movements tend to cluster together.
Strengths:<br>
  -Helps in understanding and predicting price volatility.
  -Widely used for risk management and options pricing.
Limitations:<br>
  -Primarily targets volatility, not actual price direction or magnitude.
  -Can be sensitive to model specification and parameter estimation.


## LSTM<br>
A type of recurrent neural network (RNN) designed to capture long-term dependencies in sequential data (e.g., time series).<br>
Key Characteristics:<br>
    -Capable of learning complex, non-linear relationships.
    -“Memory cells” allow the network to retain information over many time steps.
Strengths:<br>
    -Can model non-linear patterns better than many traditional models.
    -Adapts well to multi-variate time series (multiple input features).
Limitations:<br>
    -Requires larger datasets to train effectively.
    -More computationally intensive compared to ARIMA and GARCH.
    -Prone to overfitting if not regularized or tuned properly.

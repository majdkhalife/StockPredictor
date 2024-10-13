I) Introduction:
Predicting stock prices is an impossible task. So if you came to this repository hoping to become the next Warren Buffet because of your ML skills, then sorry to say that won't work. Predicting stocks correctly implies that you have a deep understanding on human psychology, which is simply impossible, as humans are emotional creatures who are impossible to predict.
However, we can use a machine learning approach to forecast future prices by training a model on historical data and projecting ahead.

II) How will we be estimating future stock prices?
We will be using a method called time series forecasting. This technique predicts future events by analyzing trends of the past, holding the assunmption that future trends will be similar to historic ones.
Firstly, we will have to learn a little about lagged features and their importance in us attempting to predict stock prices.
Lagged features are feature engineering techniques used to capture the temporal dependencies and patterns in the time series data.
A lagged feature is created by taking the value of a variable at a previous time point and including it as a feature in the model at the current time point.

What model will we be using?
We will be using the LSTM model. LSTM stands for Long short term memory.
At each time step, the LSTM processes the input and updates the cell state by controlling the information flow through these gates.
The forget gate decides what to remove from the cell state.
The input gate decides what to add from the current input.
The output gate filters the final output for the current time step.

# StockPredictionAi
This notebook creates a complete model to predict the price of a stock. In this example we predict the price of GS. We use several different data inputs to form three different datasets. We use technical indicators with historical data, autoregressive integrated moving average (ARIMA) for the stock function approximation, and long short-term memory (LSTM)  to train on the highest correlated asset. We then concatenate all of the datasets together and run XGBoost for feature importance. We then train the total dataset on a generative adversarial network (GAN). 

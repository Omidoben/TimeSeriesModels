
# Stock Price Prediction using LSTM in R






## Overview

This project demonstrates how to build a Long Short-Term Memory (LSTM) network in R using the torch package to predict stock prices. Specifically, it predicts the Open stock price using a time series of 14 days' historical data. The model processes these sequences of daily stock prices and forecasts the price for the next day.

## Key Features
1) Time Series Modeling: The model is trained on stock price data to predict the next day's open price based on a sequence of the past 14 days.

2) LSTM Architecture: Utilizes a Long Short-Term Memory (LSTM) network for sequential data modeling. 
R & Torch Integration: Implements the neural network using torch in R, enabling efficient deep learning. It consists of the following layers:
- Input layer: Takes a sequence of 14 daily prices.
- LSTM layers: Captures the sequential dependencies in the time series data.
- Fully connected layer: Produces the final prediction.

3) Predictive Performance: The model is designed to capture patterns in stock prices and improve forecast accuracy over time.

4) Visualization of Predictions: After fitting the model, predictions are visualized on the test data, focusing on the first 6 months of 2022 to evaluate how well the model performs.

### Libraries
- Torch
- Luz
- Tidyverse
- feasts
- tsibble
- fabbletools

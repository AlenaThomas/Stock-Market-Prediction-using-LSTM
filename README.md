# STOCK MARKET PREDICTION USING LSTM MODEL

## Project Overview:
In this project, we aim to predict future stock prices of META using an LSTM (Long Short-Term Memory) model, a type of recurrent neural network (RNN) known for time series analysis. The LSTM model will learn patterns from historical stock price data and make predictions for future prices.

## Dataset:
The publically available dataset containing historical stock price data for the target stock(s) of META used in this project is collected from Yahoo Finance website (https://finance.yahoo.com/quote/META/history).

The dataset includes features like opening price, closing price, volume, etc. and contains data fromo 2012 - present. We preprocess the data, splitting it into training and testing sets, and perform any necessary data transformations.

## Model Training:
The LSTM model is built using TensorFlow and trained on the training dataset. We employ techniques like regularization and dropout to prevent overfitting.

## Evaluation and Results:
Once the model is trained, we evaluate its performance on the testing dataset. We compute the root mean squared error (RMSE) to assess the model's accuracy. We visualize the predicted stock prices alongside the actual prices to gain insights into the model's performance.

![image](https://github.com/AlenaThomas/Stock-Market-Prediction-using-LSTM/assets/143086486/c6b17150-04ee-4cd3-8f82-b5df807c7e59)

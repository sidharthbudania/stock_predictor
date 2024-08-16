# Stock Price Prediction using LSTM
This project demonstrates how to predict future stock prices using an LSTM neural network with Python.

#Tools and Libraries
Python, Google Colab, TensorFlow & Keras, pandas, numpy, scikit-learn, yahoo_fin, matplotlib.pyplot

#Workflow
Load Data: Retrieve stock data using yahoo_fin.
Preprocess Data: Use only the closing prices, scale them between 0 and 1.
Prepare Data: Create shifted sequences for predicting future prices.
Build and Train LSTM Model: Sequential model with LSTM, Dropout, and Dense layers.
Predict Prices: Forecast stock prices for the next 3 days.
Evaluate Results: Plot predictions vs. actual prices.

#Accuracy and Analysis
Mean Squared Error (MSE): 3.5121
Root Mean Squared Error (RMSE): 1.8741
Mean Absolute Error (MAE): 1.3429
R-squared (R²): 0.9857
Custom Accuracy (Trend Prediction): 83.67%

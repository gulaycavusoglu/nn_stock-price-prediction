# Neural Network for Next-Day Stock Price Prediction (University Project)
This module implements a neural network regression model using TensorFlow/Keras to forecast Tesla’s next-day closing price as part of a university project. The approach involves the following steps:

# Data Preprocessing:
Historical stock data (from 04/01/2023 to 26/07/2024) is processed to format dates, compute daily returns, and scale the 'Close' prices.

# Feature Engineering:
A rolling window method is applied to generate time-series features from the 'Close' prices, enabling the model to capture temporal dependencies.

# Model Architecture:
The neural network features an input layer, two hidden layers with ReLU activation functions, and an output layer that produces a continuous value representing the predicted next-day closing price.

# Training & Evaluation:
The model is trained on 80% of the dataset and evaluated on the remaining 20% using Mean Squared Error (MSE) and Mean Absolute Error (MAE) as performance metrics.

# Visualization:
The predicted closing prices are plotted alongside the actual values, allowing for a visual comparison of the model's performance.

# stock-market-predictor

This Python script evaluates the performance of three stock price prediction models: LSTM, Random Forest, and Support Vector Regressor (SVR). It uses historical stock data, trains each model, generates predictions, evaluates them using Mean Squared Error (MSE) and R² Score, and saves the visualizations of predicted vs. actual prices.

# Features:

-Supports multiple stock predictions.

-Evaluates models based on R² Score and Mean Squared Error.

-Visualizes and saves prediction results for each model and stock.

-Handles data preparation, model training, prediction, and evaluation in a single script.


# Dependencies:

-Python 3.x

-numpy

-pandas

-scikit-learn

-matplotlib

-tensorflow

WARNING! Tensorflow does NOT work on Python 3.6.4+. In order to run this program, you must downgrade.

# Usage:

Ensure stocks_data.csv is in the data/ folder.

Run the script: python evaluation.py

Evaluation metrics (MSE and R²) will be printed in the console. Prediction plots will be saved in the results/ directory.

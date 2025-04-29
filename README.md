# Stock Market Predictor AI

A Python-based machine learning project that compares the performance of three predictive models—LSTM (Long Short-Term Memory), Random Forest Regressor, and Support Vector Regressor (SVR)—for forecasting stock prices using historical data.

# Key Features

Multi-Model Comparison: Trains and evaluates LSTM, Random Forest, and SVR models on historical stock data.

Automated Pipeline: Handles data loading, preprocessing, model training, prediction, and evaluation within a single script.

Model Evaluation: Measures and compares performance using Mean Squared Error (MSE) and R² Score.

Data Visualization: Generates and saves line plots comparing predicted vs. actual stock prices for each model.

Multi-Stock Support: Capable of evaluating multiple stocks in one run.

# Technologies Used

Languages: Python 3.x

Libraries: NumPy, Pandas, Scikit-learn, Matplotlib, TensorFlow

⚠️ Note: For TensorFlow compatibility, Python version must be ≤ 3.6.3.

# Usage Instructions

Place your dataset (stocks_data.csv) in the data/ directory.

Run the script:
python evaluation.py

Model performance metrics (MSE and R²) will be printed to the console.
Prediction visualizations will be saved in the results/ folder.

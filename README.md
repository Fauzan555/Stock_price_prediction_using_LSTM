# 📈 Stock Price Prediction using LSTM

This project demonstrates how to predict stock prices using Deep Learning (LSTM).
It covers the end-to-end workflow — from data collection, preprocessing, model training, evaluation, and future forecasting.

# 🚀 Features

📊 Data collection using yfinance

🔧 Data preprocessing and feature scaling

🧠 LSTM model built with TensorFlow/Keras

⚡ Hyperparameter tuning for better performance

📉 Training, validation, and forecasting (30 days)

# 🧑‍💻 Workflow

Load historical stock price data with yfinance

Preprocess and scale the data using MinMaxScaler

Prepare input sequences (60-day closing prices)

Train an LSTM neural network with Keras

Evaluate model performance on test data

# 📊 Results

✅ Model captures short-term stock price movements effectively.

✅ Validation loss converges to a small value (~0.001–0.002).

✅ Forecasting demonstrates realistic upward/downward patterns.

# 📌 Tech Stack

Python

TensorFlow / Keras (Deep Learning)

yfinance, pandas, numpy, matplotlib (Data handling & visualization)

joblib (Saving Scaler)

# ⚙️ How to Run

Follow these steps to run the project locally:

# 1. Clone the repository
git clone https://github.com/your-username/Stock-Price-Prediction.git
cd Stock-Price-Prediction

# 2. Create a virtual environment (recommended)
python -m venv venv
source venv/bin/activate    # For Linux/Mac
venv\Scripts\activate       # For Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run Jupyter Notebook
jupyter notebook


Then open Stock_Price.ipynb and run the cells step by step.

# 📌 Future Improvements

Try different architectures (GRU, Transformer models)

Integrate external features (volume, technical indicators, news sentiment)

Build a Flask/FastAPI app for real-time predictions

Forecast the next 30 days

All training and evaluation steps are documented in Stock_Price.ipynb.

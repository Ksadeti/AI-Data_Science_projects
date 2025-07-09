📈 Stock Price Forecasting with RNN & LSTM

This project uses deep learning techniques — specifically Simple RNN and LSTM — to forecast stock closing prices based on historical data. The dataset used includes Yahoo's AABA stock data from 2006 to 2018.

🚀 Project Highlights

🔍 Exploratory Data Analysis (EDA) with moving averages, volume trends, and daily returns

🧼 Data Preprocessing: Handling time series structure, scaling, and windowing

🧠 Modeling with RNN: Built and trained a lightweight Recurrent Neural Network for prediction

🔄 Modeling with LSTM: Leveraged Long Short-Term Memory to capture complex temporal dependencies

📊 Performance Evaluation using MAE, MSE, and validation trends

📉 Forecasting: Predicting future values using recursive multi-step prediction


📈 Main Tools Used

Python, Pandas, NumPy

TensorFlow / Keras

Matplotlib, Seaborn

Scikit-learn (MinMaxScaler)

TimeseriesGenerator for sequence building


🧠 Results Summary

RNN model: Fast and lightweight, low error (MAE ≈ 0.108)

LSTM model: Captures long-term patterns better, good forecast but slightly overfit after a few epochs

Both models were used for multi-step forecasting of future prices

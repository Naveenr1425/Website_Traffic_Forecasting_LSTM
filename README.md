# Website Traffic Forecasting using LSTM

## 📌 Project Overview
This project uses Long Short-Term Memory (LSTM), a deep learning algorithm, to forecast future website traffic based on historical page-view data. It helps understand traffic patterns and supports better server resource planning.

## 🎯 Objectives
- Analyze historical website traffic.
- Handle missing values and normalize data.
- Train an LSTM model to predict future traffic.
- Evaluate performance using MAE and RMSE.
- Visualize actual vs. predicted traffic and forecast the next 7 days.

## 📊 Dataset
- **Source:** Kaggle – Web Traffic Time Series Forecasting
- **File:** `train_1.csv`
- **Data used:** 5 web pages across 550 daily observations.

## 🛠️ Technologies Used
- Python
- Pandas and NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Google Colab

## ⚙️ Methodology
1. Load the website traffic dataset.
2. Handle missing values.
3. Normalize traffic values using `MinMaxScaler`.
4. Create sequences using the previous 30 days of data.
5. Train an LSTM model.
6. Evaluate predictions using MAE and RMSE.
7. Plot actual vs. predicted traffic and forecast future traffic.

## 🧠 Model Architecture
- LSTM layer – 64 units
- Dropout layer – 20%
- Dense layer – 32 neurons
- Output layer – 5 neurons


# Hybrid ARIMA-LSTM Framework for LAN Latency Prediction

## Overview
This project presents a Hybrid ARIMA-LSTM Framework for LAN Latency Prediction, Network Stability Classification, and Anomaly Detection. The system combines statistical forecasting, deep learning, and machine learning techniques to predict LAN latency trends, classify network stability, and detect abnormal network behavior in real-time environments.

The framework integrates ARIMA for linear trend analysis and LSTM for nonlinear temporal pattern learning to improve prediction accuracy and network performance monitoring.

---

## Models Used

### Time-Series Forecasting
- ARIMA
- LSTM
- Hybrid ARIMA + LSTM

### Classification
- Random Forest

### Anomaly Detection
- One-Class SVM
- Isolation Forest
- Autoencoder

---

## Dataset Details
The dataset consists of timestamped LAN latency records collected from different network environments.

### Features Included
- Timestamp
- Network Type (Wired/Wireless)
- Source IP Address
- Destination IP Address
- Local Average Latency
- Remote Average Latency
- Stability Labels

The dataset was preprocessed using:
- Rolling Mean Smoothing
- Stationarization
- Normalization
- Sequential Feature Engineering

---

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Statsmodels
- Matplotlib
- Seaborn

---

## Performance Highlights
- Random Forest Classification Accuracy: 97.5%
- Hybrid ARIMA-LSTM RMSE: 0.0051
- Effective real-time anomaly detection using One-Class SVM and Isolation Forest

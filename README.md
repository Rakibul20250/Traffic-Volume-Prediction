# Traffic Volume Prediction using Deep Learning

This project applies deep learning techniques (LSTM and CNN-LSTM) to predict **hourly traffic volume** 
based on weather and time-related features.

## 📊 Dataset
- Features: holiday, temp, rain, snow, clouds, weather, date_time
- Target: traffic_volume

## 🧠 Models
- LSTM
- CNN-LSTM

## 📈 Results
LSTM Model → RMSE: 369.50, MAPE: 12.62%,R²: 0.9648
CNN+LSTM Model → RMSE: 393.81, MAPE: 13.30%,R²: 0.9600

## 🚀 Future Work
- Hyperparameter tuning
- Attention-based models
- External data (events, accidents, etc.)

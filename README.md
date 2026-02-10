# Wind-Power-Forecasting-ML
📌 Project Overview

      Wind power is a key renewable energy source, but its intermittent nature makes accurate forecasting challenging.
      This project focuses on forecasting wind power generation using both statistical and deep learning models to improve prediction accuracy and reliability.
      
      We implemented and compared:
      
      ARIMA (statistical time-series model)
      LSTM (Long Short-Term Memory network)
      GRU (Gated Recurrent Unit network)
      The goal is to analyze model performance and identify the most effective approach for wind power forecasting.

🎯 Objectives

      To preprocess and analyze wind power time-series data
      To implement ARIMA, LSTM, and GRU models
      To compare traditional statistical methods with deep learning models
      To evaluate forecasting accuracy using performance metrics

🧠 Models Used

1. ARIMA (AutoRegressive Integrated Moving Average)
      Classical time-series forecasting model
      Suitable for linear and stationary data
      Used as a baseline model
2. LSTM (Long Short-Term Memory)
      Recurrent neural network designed for long-term dependencies
      Handles non-linear patterns in wind data effectively
3. GRU (Gated Recurrent Unit)
      Lightweight alternative to LSTM
      Faster training with comparable performance

🛠️ Technologies & Tools

Programming Language: Python
Libraries:
      NumPy
      Pandas
      Matplotlib / Seaborn
      Scikit-learn
      TensorFlow / Keras
      Statsmodels
Environment: Jupyter Notebook

🔄 Workflow

      Data Collection
      Data Preprocessing & Normalization
      Time-Series Analysis
      Model Training (ARIMA, LSTM, GRU)
      Forecasting
      Performance Evaluation
      Result Comparison

📊 Evaluation Metrics

      Mean Absolute Error (MAE)
      Mean Squared Error (MSE)
      Root Mean Squared Error (RMSE)

✅ Results & Observations

     ARIMA performs well on stationary data but struggles with non-linearity
     LSTM captures long-term dependencies effectively
     GRU provides faster training with competitive accuracy
     Deep learning models outperform ARIMA for complex wind patterns

🚀 Future Scope

     Hyperparameter tuning for improved accuracy
     Hybrid ARIMA–LSTM models
     Real-time wind power forecasting
     Integration with IoT and smart grid systems

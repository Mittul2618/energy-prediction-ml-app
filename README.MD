⚡ Energy Consumption Prediction Using Machine Learning

This project presents a machine learning-based system for short-term residential electricity consumption forecasting. Using a multi-regional dataset enriched with contextual metadata, the system benchmarks the performance of three popular models Random Forest,XGBoost, and LSTM and deploys the best-performing one via a user-friendly Streamlit application.

📌 Project Overview

- Objective: Predict short-term household energy usage using historical and contextual data.
- Models Used:
- Random Forest
- XGBoost
- Long Short-Term Memory (LSTM)
- Deployment:https://4cb9-104-196-178-135.ngrok-free.app/
- Data Source: Hanžel et al. (2025), multi-region dataset with metadata like insulation quality, heating type, etc.

🚀 Features

- Time-based feature engineering (hour, weekday, rolling averages)
- Comparative model evaluation using RMSE, MAE, and R²
- Real-time user input for custom predictions
- Interactive Streamlit interface with visualization
- Modular architecture (data preprocessing → model training → deployment)

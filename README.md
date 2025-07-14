#☁️ Rain Forecasting App 🌧️

A simple and interactive Streamlit web app that predicts whether it will rain tomorrow based on today's weather data using a trained Random Forest model.

---

## 🚀 Features

- 🌧️ Predicts **Rain Tomorrow** using weather parameters like temperature, humidity, pressure, and wind speed.
- 📊 Visualizes weather variable relationships with interactive scatter plots.
- 📈 Sidebar data insights from historical rain data.
- 🖥️ Built with Python, Streamlit, scikit-learn, and pandas.

---

## 🧠 Machine Learning Model

- **Algorithm**: RandomForestClassifier
- **Trained on**: `rain_forecasting.csv` dataset
- **Target**: `RainTomorrow` (Yes/No)

---

## 🗂️ Project Structure

rain_forecasting_app/
├── app/
│ └── weather_forecast.py # Streamlit app script
├── data/
│ └── rain_forecasting.csv # Weather dataset
├── model/
│ └── rain_predictor_model.pkl # Trained ML model
├── requirements.txt # Project dependencies
├── README.md # Project overview (this file)
└── .gitignore # Files to ignore
# Solar & Bitcoin Time Series Forecasting with SARIMAX

This project explores the potential predictive relationship between solar activity and Bitcoin prices using time series forecasting. It was developed as part of my final project for the Ironhack Data Analytics Bootcamp, showcasing my ability to apply statistical modeling and machine learning techniques to real-world data.


## 🔍 Project Overview

Goal: Predict Bitcoin prices using sunspot data (a proxy for solar activity) and historical BTC price.

Model Used: SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous factors)

Tech Stack: Python, Pandas, Statsmodels, Matplotlib, Plotly, Pickle

Key Concepts: Time Series Analysis, Feature Engineering, Supervised ML, Forecasting---


## 💼 Why This Project Matters

This project demonstrates:

Proficiency in time series forecasting and advanced statistical modeling

Ability to work with multi-source data and clean, merge, and transform it

Competence in developing and evaluating predictive models (train/test split, diagnostics)

Effective use of Python tools and visualizations to communicate results

Understanding of model deployment considerations (saving/loading models with pickle)


## 🚀 Features

- Time series visualization and decomposition
- Stationarity testing (ADF Test)
- SARIMAX modeling with exogenous features
- Model diagnostics and evaluation
- Forecast visualization

---

## 📁 Project Structure

```
solar-bitcoin-arima/
├── data/               <- Raw or processed datasets
├── notebooks/          <- Jupyter Notebooks for exploration
├── models/             <- Saved SARIMAX models
├── src/                <- Reusable Python scripts
├── outputs/            <- Forecasts and plots
├── README.md
└── requirements.txt
```

---

## 🧪 Tech Stack

- Python
- pandas, numpy
- statsmodels (SARIMAX)
- matplotlib, seaborn
- pickle

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/solar-bitcoin-arima.git
cd solar-bitcoin-arima
pip install -r requirements.txt
```

---

## 📈 Forecast Results

Include your forecast visualization here, e.g.:

![Forecast](outputs/forecast_plot.png)

---

## 📂 Using the Saved Model

```python
import pickle

with open("models/sarimax_model.pkl", "rb") as f:
    model = pickle.load(f)

forecast = model.get_forecast(steps=10, exog=exog_future_data)
```

---

## 🙌 Acknowledgements

Built during the Ironhack Data Analytics Bootcamp as a final project — merging interests in Bitcoin, energy, and time series forecasting.

---

## 🔗 License

MIT License


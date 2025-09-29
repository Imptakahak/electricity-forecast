# Electricity Demand Forecasting

A minimal project to forecast short-term electricity demand using time series models.
This project demonstrates the workflow from data preprocessing to model evaluation.

## 📊 Features
- Time series preprocessing (datetime index, resampling)
- Visualization of demand trends
- Forecasting with ARIMA and Prophet
- Model evaluation with RMSE, MAPE

## 📂 Project Structure
- `notebooks/demand_forecast.ipynb`: step-by-step analysis with plots
- `src/train.py`: minimal script version
- `data/sample_electricity.csv`: sample dataset

## ⚙️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/demand_forecast.ipynb

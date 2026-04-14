# Xi'an PM2.5 Predictive Modeling 🌬️

## Project Overview
This project focuses on forecasting hourly PM2.5 concentrations in Xi'an, China. It leverages a **Random Forest Regressor** to analyze time-series patterns and environmental factors.

## Features
- **Data Scraping:** Automated API-based data collection from Open-Meteo.
- **Feature Engineering:** Implementation of time-lag features (Lag-1h, Lag-2h, Lag-24h) to capture pollution inertia.
- **High Accuracy:** Achieved an **R² score of 0.9501**, demonstrating robust predictive capabilities.

## Tech Stack
- **Language:** Python 3
- **Libraries:** Pandas, Scikit-learn, Matplotlib, Requests
- **Model:** Random Forest Regressor

## Results
The model effectively captures the seasonal and hourly fluctuations of PM2.5 in the Xi'an basin area.
- **RMSE:** 16.54 μg/m³
- **R² Score:** 0.9501

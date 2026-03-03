# Predictive-Maintenance-System-KenGen
An end-to-end Machine Learning system designed to predict failures in power generation assets (Wind, Hydro, Geothermal) using multi-sensor SCADA data.

## 🇰🇪 Project Overview
This project develops a predictive maintenance system specifically modeled for **KenGen (Kenya Electricity Generating Company)**. The goal is to move from "Run-to-Failure" to "Proactive Maintenance" for critical energy infrastructure.

###  The Model
- **Problem Type:** Remaining Useful Life (RUL) prediction & Anomaly Detection.
- **Algorithms:** Random Forest / LSTM (Long Short-Term Memory).
- **Data Source:** Fused sensor data (Vibration, Temperature, Pressure) from Kaggle.

###  The System
- **Data Pipeline:** Modular Python scripts for cleaning and feature engineering.
- **Dashboard:** Interactive Tableau dashboard for plant engineers to monitor "Asset Health Scores."
- **Stack:** Python, Scikit-Learn, Pandas, Tableau, GitHub Actions.

##  Project Structure
- `/data`: Raw and processed sensor datasets.
- `/src`: Modular Python scripts (`data_processor.py`, `model_engine.py`).
- `/notebooks`: Exploratory Data Analysis (EDA).
- `/dashboards`: Tableau workbook files.

##  How it Works
1. **Ingestion:** Real-time (simulated) sensor data is pulled into the system.
2. **Analysis:** The model calculates the probability of failure for each asset.
3. **Visualization:** Alerts are pushed to the Tableau dashboard for maintenance scheduling.

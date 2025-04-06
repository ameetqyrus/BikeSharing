# 🚲 Bike Sharing Demand Analysis

This repository contains a Jupyter Notebook that performs exploratory data analysis and simple linear regression to understand factors affecting the demand for shared bikes.

## 📁 Files
- `Bike_Sharing.ipynb` — Jupyter notebook with code and analysis.
- `download.csv` — Dataset containing daily bike rental data.

## 📊 Dataset Description
The dataset (`download.csv`) includes:
- Date and time features: `dteday`, `mnth`, `weekday`, `season`, `yr`
- Weather-related features: `temp`, `atemp`, `hum`, `windspeed`, `weathersit`
- Rental indicators: `holiday`, `workingday`
- User counts: `casual`, `registered`
- Target variable: `cnt` (total rentals per day)

## 🎯 Objective
To explore how temperature affects daily bike rentals using:
- Exploratory data analysis
- Correlation analysis
- Simple linear regression (using `temp` as the sole predictor)

## 📈 Analysis & Visualization
The notebook includes:
- Distribution plots of bike rentals
- Scatter plots of temperature and humidity vs rentals
- Box plots for rentals across seasons
- Correlation heatmap among numerical variables

## 🧪 Model Summary
- **Model Used:** Simple Linear Regression
- **Feature Used:** `temp`
- **Target:** `cnt` (total rentals)
- **Evaluation Metrics:**
  - R² Score (train and test)
  - RMSE (train and test)
- **Visualization:** Actual vs Predicted plots on training and test data

## 🔍 Key Insights
- **Temperature** is positively correlated with bike rentals.
- A simple linear regression model using temperature provides a reasonable estimate of rental demand.
- The model's predictions follow the actual values fairly closely, especially for training data.

## ▶️ How to Run
1. Open `Bike_Sharing.ipynb` using Jupyter Notebook or JupyterLab.
2. Run all cells to reproduce the visualizations and model outputs.

## ✅ Requirements
Install the necessary packages using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

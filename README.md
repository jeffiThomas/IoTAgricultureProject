# IoTAgricultureProject

## Project Overview

This project implements an IoT-based smart agriculture system for environmental monitoring and predictive analytics. Sensor data was collected, processed, and analyzed to support two primary machine learning tasks:

Soil Moisture Prediction (Regression Models)

Environmental Temperature Forecasting (LSTM Time Series Model)

The system demonstrates how IoT sensor data can be used to support data-driven agricultural decision-making under limited data constraints.

## Notebooks
1. Data Loading and Merging

This notebook:
- Loads raw IoT sensor data
- Cleans and preprocesses the data
- Merges datasets into a unified structure
- Saves the processed dataset as a .parquet file for efficient storage

2. Exploratory Data Analysis (EDA)

This notebook:
- Examines feature distributions
- Analyzes correlations between environmental variables
- Visualizes time-series patterns
- Identifies anomalies and trends in soil moisture and temperature

3. Modeling

This notebook implements two machine learning approaches:

Regression Models (Soil Moisture Prediction):
- Linear Regression
- Decision Tree
- Multi-Layer Perceptron (MLP)

Performance is evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

Time Series Forecasting:
- Long Short-Term Memory (LSTM) neural network
- Predicts short-term environmental temperature
- Evaluated using MAE and RMSE

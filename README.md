# Energy Consumption Forecasting with Time-Series Models

## Project Overview
This project focuses on forecasting household energy consumption using classical statistical models and deep learning approaches.  
The goal is to analyze how different time-series models perform on appliances with **regular vs irregular usage patterns**, using real-world smart meter data.

This project is based on my MSc thesis in *Data-Driven Decision Making* (University of Patras).

---

## Business / Analytical Problem
Accurate energy forecasting is essential for:

- Smart home optimization  
- Energy cost reduction  
- Demand-side energy management  

Different household appliances exhibit very different consumption behaviors.  
This project evaluates **which forecasting models are best suited for each usage type**.

---

## Dataset

| Characteristic | Description |
|--------------|------------|
| Sampling | 1 min (normal), 50 ms (power spikes >100W) |
| Period | September 2022 (30 days) |
| Appliances | Refrigerator, Water Heater |
| Variables | Active Power, Voltage, Current, Crest Factor, etc. |

**Data preprocessing included:**
- Missing value handling  
- Resampling & alignment  
- Noise smoothing  

---

## Models Implemented

| Category | Models |
|--------|------|
| Statistical | ARIMA, SARIMA, SARIMAX |
| Decomposition | STL, MSTL + SARIMA |
| Deep Learning | LSTM, CNN–LSTM |

---

## Key Insights

### Refrigerator
- Strong seasonal and cyclical patterns  
- SARIMA and SARIMAX delivered the most accurate forecasts  
- Statistical models were sufficient for predictable behavior  

### Water Heater
- Irregular, non-linear usage  
- LSTM and SARIMAX achieved better performance  
- External factors strongly influenced consumption  

---

## Technologies

Python | pandas | numpy | scikit-learn | statsmodels | TensorFlow / Keras | Jupyter Notebook

---

## Why This Project Matters
This project demonstrates my ability to:

- Clean and preprocess real-world time-series data  
- Build and evaluate forecasting models  
- Compare statistical and machine learning approaches  
- Generate analytical insights for decision making  

---

## Future Work
- Hybrid SARIMA–LSTM models  
- Real-time forecasting pipelines  
- Smart home energy optimization  

---

## Author
**Christina Marinopoulou**  
Junior Data Analyst / BI & Forecasting  
MSc in Data-Driven Decision Making

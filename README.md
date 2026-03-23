# ⚡ EV Charging Demand Forecasting

A machine learning–driven predictive framework for short-term electric vehicle (EV) charging demand estimation.  
This project leverages temporal patterns, derived operational indicators, and ensemble regression models to support intelligent energy management and smart grid demand planning.

---

## 📌 Project Overview

The rapid adoption of electric vehicles introduces significant challenges in managing charging infrastructure and maintaining grid stability.  
This project develops a structured data-driven forecasting pipeline designed to capture time-dependent charging behaviour and system utilization dynamics for improved demand prediction accuracy.

---

## 🎯 Objectives

- Forecast short-term EV charging demand using machine learning techniques  
- Model temporal consumption patterns and operational system indicators  
- Support smart charging station scheduling and grid load optimization  
- Provide a baseline experimental framework for energy forecasting research  

---

## 📊 Methodology

The forecasting workflow consists of systematic feature engineering and supervised learning models.

### Time-Series Feature Engineering
- Hourly demand representation  
- Day-of-week variability  
- Monthly trend indicators  
- Peak hour and weekend flags  

### Derived System Indicators
- Charging intensity estimation  
- Fleet utilization characteristics  
- Demand stress representation  
- Behaviour-influenced synthetic features  

### Temporal Dependency Modelling
- Lag demand variables  
- Rolling statistical measures  

### Implemented Machine Learning Models
- Linear Regression (baseline model)  
- Random Forest Regressor  
- XGBoost Regressor  

---

## 📈 Performance Evaluation

Model effectiveness is evaluated using standard regression metrics:

- Root Mean Square Error (RMSE)  
- Mean Absolute Error (MAE)  
- Coefficient of Determination (R² Score)  

---

## 🧠 Potential Applications

- Smart EV charging station management  
- Energy demand planning for distribution networks  
- Fleet charging optimization  
- Sustainable transportation research  
- Intelligent smart grid operations  

---

## 🛠️ Technology Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib  
- Jupyter Notebook  

---

## 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/ArShx17/EV-charging-demand-forecasting
cd EV-charging-demand-forecasting
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Project

```bash
jupyter notebook
```

Open **forecasting.ipynb** and execute all cells to reproduce forecasting results.

---

## 🔮 Future Enhancements

- Time-series cross-validation implementation  
- Deep learning-based forecasting models (LSTM / GRU)  
- Explainable AI techniques for feature interpretation  
- Probabilistic demand forecasting  
- Real-time smart grid deployment integration  

---

## 📄 License

This project is developed for academic research and educational purposes.
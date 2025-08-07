# Is Deep Learning Always Better?  
### A Comparative Case Study of ARIMAX and GRU for Stock Price Prediction

This repository contains the implementation of a research project that investigates whether deep learning models such as GRU always outperform traditional statistical models like ARIMAX in the task of stock price prediction. The case study is conducted using stock data from three major companies in the Iranian stock market.

---

## Models Compared

- **ARIMAX (AutoRegressive Integrated Moving Average with Exogenous Variables)**
- **GRU (Gated Recurrent Unit)** — a deep learning model for time series prediction

---

## Feature Selection Methods

- **Correlation Analysis**
- **XGBoost Feature Importance**

---

## Evaluation Metrics

- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- Mean Absolute Percentage Error (MAPE)  
- R² Score (Coefficient of Determination)

---

## Dataset

Stock market data from three companies:
- Bank Saderat Iran 
- Iran Khodro (IKCO)
- Mobarakeh Steel Company

Data was preprocessed and engineered with technical indicators and lag-based features.

---

## Results Summary

- ARIMAX outperformed GRU in most data configurations, especially when using stable and linear features.
- GRU showed competitive results only with simple, correlation-based features.
- Feature selection and data quality significantly impact model performance.

---


## How to Run

1. Clone the repo:
```bash
git clone https://github.com/your-username/stock-price-prediction-arimax-vs-gru.git
cd stock-price-prediction-arimax-vs-gru


pip install -r requirements.txt



jupyter notebook notebooks/Model_Comparison.ipynb

```
## Models and Output Visualizations

### Forecasting with ARIMAX and XGBoost – Saderat Bank
![ARIMAX Output](results/Saderat_Saderat_ARIMAX_XGBoost.png)

---

### Forecasting with GRU and XGBoost – Saderat Bank

![GRU Output](results/Saderat_Saderat_GRU_XGBoost.png)

---

### Feature Correlation Heatmap

![Heatmap](results/output.3.png)

---

### Forecasting Foolad Stock with ARIMAX

![Foolad ARIMAX](results/folad_folad_ARIMAX_HEATMAP.png)

---

### Forecasting Foolad Stock with GRU

![Foolad GRU](results/folad_folad_GRU_HEATMAP.png)


## Conclusion
While deep learning is powerful, it is not always superior. In stock price forecasting, classical models like ARIMAX may outperform GRU, especially when the data structure is relatively linear and stable.

## Author
Seyedeh Bita Amiri

Artificial Intelligence Researcher

GitHub • LinkedIn

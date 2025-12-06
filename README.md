# 🚕 NYC Taxi Demand Forecasting — Experimentation Repository

This repository contains all experimentation, research, and prototyping work for building a high-resolution 15-minute taxi demand forecasting system.  
It includes data preprocessing trials, clustering experiments, feature engineering exploration, baseline modeling, and hybrid model development.

---
## 🚀 Live  App  
Explore the working:

🔗 **https://apoorvtechh-dashboard-demand-prediction-app-gx2szx.streamlit.app/**

## 🔬 What This Repo Contains
- Data cleaning experiments (Dask, outlier removal)
- Coordinate clustering with MiniBatchKMeans
- Region-wise resampling & EWMA smoothing tests
- Lag + rolling window feature engineering trials
- Baseline model experiments (Prophet, XGBoost, SARIMA)
- Hybrid Prophet + XGBoost experimentation
- Region-wise evaluation & MAPE comparison
- Visualization notebooks and plots
- Early pipeline design before productionizing

---

## 📁 Related Production Repository
The final production-ready pipeline is available here:

👉 **Final Project Repo:**  
https://github.com/apoorvtechh/demand_forecasting

This experimentation repo represents the research phase; the final repo contains a full DVC pipeline, modular code, and the final hybrid forecasting system.

---

## 🧰 Tech Stack Used
- **Python**
- **Dask** for large-scale data processing  
- **Pandas / NumPy**  
- **Scikit-learn** (scaling, clustering)  
- **MiniBatchKMeans**  
- **Prophet** for trend & seasonality  
- **XGBoost** for machine learning forecasting  
- **Matplotlib / Seaborn** for visualization  
- **Jupyter Notebooks**  

---

## 🧪 Purpose of This Repo
This repo was used to:
- Test multiple modeling strategies  
- Understand region-wise behavior  
- Compare Prophet vs XGBoost vs Hybrid  
- Determine best smoothing, lag windows, and hyperparameters  
- Validate why hybrid modeling significantly improves MAPE  

All successful experiments were later moved into the production repository.

---

## 📎 Useful Links
🔗 **Experimentation Repo:** https://github.com/apoorvtechh/demand_preidction_experimentation  

🔗 **Final Demand Forecasting Repo:** https://github.com/apoorvtechh/demand_forecasting

🔗 **Synopsis Link Repo:** https://apoorvtechh-synopsis-dp-app-wxbcw6.streamlit.app/  

---

## 📄 License
This project is for educational and research purposes.


# AID_843_STDA

## Spatio-Temporal Data Analysis (STDA)

This repository contains our group work for **AID843 – Spatio-Temporal Data Analysis** at IIIT Bangalore.  
All three assignments (A1, A2, A3) are organised into separate folders.

---

## 📁 Repository Structure
```bash
AID_843_STDA/
│
├── Assignment 1/
│   ├── AID 843 Programming Assignment...
│   ├── Data_preprocessing.ipynb
│   ├── LISA_Clustering_and_Correlation.ipynb
│   ├── Regression_Models.ipynb
│   ├── STDA Notebook.ipynb
│   ├── STDA_Assignment1_Report.pdf
│   ├── Spatial_Stationarity_Heteroginity.ipynb
│   └── Trees Dataset.csv
│
├── Assignment 2/
│   ├── Images Book1 and 2/
│   ├── Images Book Final/
│   ├── A2_Project_Matrix_Report.pdf
│   ├── STDA_A2_Book1.ipynb
│   ├── STDA_A2_Book2.ipynb
│   └── STDA_A2_Final.ipynb
│
├── Assignment 3/
│   ├── Images/
│   ├── A3_Guidelines.pdf
│   ├── STDA_A3_draft1.ipynb
│   ├── STDA_A3_draft2_updated.ipynb
│   ├── STDA_A3_understanding_dataset.ipynb
│   └── STDA_Assignment_2.pdf
│
└── README.md
```
Each folder contains:
- Code (Jupyter notebooks / scripts)
- Intermediate outputs
- Visualisations
- Relevant documentation

---

## 📊 Dataset

We use the **Heart Disease and Stroke Mortality Dataset (1999–2019)**.

- Source: Kaggle  
- Coverage: 3,000+ U.S. counties  
- Time span: 1999 – 2019  
- Metric: Age-standardised mortality rate (per 100,000)

🔗 Dataset Link:  
https://www.kaggle.com/datasets/irakozekelly/heart-disease-and-stroke-mortality-20002019

As described in our report :contentReference[oaicite:0]{index=0}, the working dataset contains **64,737 county-year observations** after filtering.

---

## 🧠 Project Overview

This project performs **comprehensive spatio-temporal analysis** including:

### Spatial Analysis
- Choropleth Mapping
- Global Moran’s I
- LISA (Local Indicators of Spatial Association)
- Getis-Ord G* Hotspot Analysis
- Spatial Regression (SLM, SEM, GWR)

### Temporal Analysis
- STL Decomposition
- ADF, ACF, PACF
- ARIMA Forecasting
- Exponential Smoothing (SES, Holt, Holt-Winters)

### Time Series Data Mining
- PAA (Piecewise Aggregate Approximation)
- DFT (Dimensionality Reduction)
- SAX Sequence Mining
- Motif & Discord Detection
- Change Point Detection

### Machine Learning
- Spatial Classification (RF, LR, KNN, SVC)
- Temporal Regression (RF, Ridge, Linear Regression)
- Joint Spatio-Temporal Model
- Ablation Study

---

## 📈 Key Results

- Strong spatial autocorrelation (**Moran’s I ≈ 0.72**)  
- Identified **Stroke Belt clusters** in the U.S.  
- ARIMA(1,1,1) selected for forecasting  
- Spatial classification accuracy: **~91% (Random Forest)**  
- Temporal regression performance: **R² ≈ 0.97**  
- Joint spatio-temporal model outperforms individual models  

---

## 👥 Team Members

- **KNV Aditya (IMT2023033)**
- **Katakam Shashidhar Sai (IMT2023567)**
- **Hardhik Dhavala (IMT2023579)**

---

## 🔗 Repository Link

https://github.com/DHardhik/AID_843_STDA

---

## ⚙️ Requirements

Common libraries used:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- statsmodels
- geopandas
- libpysal
- esda
- spreg
- mgwr
- stumpy
- ruptures

---

## 📌 Notes

- Each assignment builds progressively on spatial, temporal, and joint analysis.
- All visualisations are generated using Python.
- Code is modular and organised per task.

---

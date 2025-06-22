<!-- HEADER -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&pause=1000&color=58D68D&center=true&vCenter=true&width=900&lines=📊+Visual+Analytics+of+WFH+in+UK+(2011–2030)+🚀" alt="Animated Header">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Science-blue?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tableau-Visualization-orange?style=for-the-badge&logo=tableau&logoColor=white"/>
  <img src="https://img.shields.io/badge/Census-LSOA%2033%2C647-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Forecast-Year%202030-purple?style=for-the-badge"/>
</p>

---

## 🌍 Overview

This repository presents a **visual analytics project** on the socio-economic factors influencing **Work From Home (WFH)** trends across **England and Wales** using census data from **2011 and 2021**, with a forecast for **2030**.  

🔍 We combined **Python analytics**, **machine learning**, and **interactive Tableau dashboards** to visualize how **employment**, **gender**, **housing**, and **transportation** shaped the WFH revolution.

---

## ✨ Highlights

- 📈 **Bayesian Linear Regression** for forecasting 2030 WFH trends  
- 🧬 **Dimensionality Reduction** via PCA and t-SNE to uncover patterns  
- 🗺️ **Geospatial Visuals** using Tableau for over 33,000+ neighborhoods (LSOAs)  
- 📊 **Interactive Dashboards** that reveal socio-economic disparities in WFH adoption  
- 🧠 Built with policymakers, planners, and researchers in mind

---

## 🧠 Project Goals

| 🎯 Objective | ✅ Method |
|-------------|-----------|
| Compare WFH rates (2011 vs 2021) | Preprocessed census datasets by LSOA |
| Cluster LSOAs by socio-economic traits | PCA & t-SNE for unsupervised learning |
| Predict WFH rates in 2030 | Bayesian Linear Regression using PyMC3 |
| Make insights explorable | Tableau dashboards with filters & KPIs |

---

## 📸 Visual Dashboard Snapshots

| 📌 Dashboard | 🖼️ Preview |
|-------------|-----------|
| **WFH Change by Region** | ![Geo WFH](dashboards/screenshots/geo_dashboard.png) |
| **Time Forecast (2011–2030)** | ![Time Series](dashboards/screenshots/timeline_forecast.png) |
| **PCA & t-SNE Cluster Views** | ![Cluster](dashboards/screenshots/cluster_tsne.png) |
| **Gender & Transport Analysis** | ![Scatter](dashboards/screenshots/gender_transport.png) |

---

## 🛠 Data Pipeline

```mermaid
flowchart TD
    A[Census Data 2011/2021] --> B[Data Cleaning (pandas)]
    B --> C[Feature Engineering]
    C --> D[Change Metrics (Δ)]
    D --> E[PCA & t-SNE (scikit-learn)]
    C --> F[Bayesian Regression (PyMC3)]
    E --> G[Tableau Dashboards]
    F --> G

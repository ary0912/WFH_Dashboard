<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=28&pause=1200&color=58D68D&center=true&vCenter=true&multiline=true&width=900&height=80&lines=🏙️+Visual+Analytics+of+Remote+Work+(WFH)+Trends+%7C+England+%26+Wales+2011–2030+📈" />
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Python%20%26%20Tableau-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Frameworks-PCA%2C%20tSNE%2C%20Bayesian%20Regression-green?style=flat-square" />
  <img src="https://img.shields.io/badge/Data%20Points-33%2C647%20LSOAs-blueviolet?style=flat-square" />
  <img src="https://img.shields.io/badge/Coverage-England%20%26%20Wales-yellow?style=flat-square" />
</p>

---

## 🌍 Overview: A Decade of Remote Work Transformation

**This project** explores the rise of Work-From-Home (WFH) practices from 2011 to 2021, using detailed census data across 33,000+ neighborhoods (LSOAs) in England and Wales.  
We uncover the **socio-economic forces** shaping this transformation and **predict the future of remote work** through advanced machine learning and interactive Tableau dashboards.

> 🧠 _It’s not just a report. It’s a policy-informing, cluster-revealing, trend-forecasting visual engine for urban transformation._

---

## 🧭 Key Objectives

| 🎯 Goal | ✅ Execution |
|--------|-------------|
| **Understand WFH Trends** | 📈 Analyzed WFH rates (2011 vs 2021) using public census data |
| **Uncover Socio-Economic Clusters** | 🧬 Used PCA and t-SNE to reveal hidden clusters |
| **Forecast the Future** | 🔮 Bayesian Linear Regression predicted WFH rates for 2030 |
| **Enable Decision Making** | 🗺️ Delivered interactive Tableau dashboards for stakeholders |

---

## 🧩 What Makes This Project Unique?

✔️ Combines **ML modeling, geospatial mapping, and visual storytelling**  
✔️ Uses **Bayesian regression** for transparent, uncertainty-aware prediction  
✔️ Integrates **dimensionality reduction (PCA & t-SNE)** for socio-economic insight  
✔️ Designed for **urban planners, HR strategists, and policy makers**  

> 🪄 _An exploration of digital equity, remote labor potential, and urban design—visually._

---

## 📸 Sneak Peek: Interactive Dashboards

| 📌 View | 🌐 Description | 🖼️ Visual |
|--------|----------------|----------|
| **1. Geo WFH Map** | WFH change from 2011 to 2021 by LSOA | ![](dashboards/screenshots/geo_dashboard.png) |
| **2. WFH Timeline** | 2011 → 2021 → 2030 (prediction) | ![](dashboards/screenshots/timeline_forecast.png) |
| **3. Clustering (PCA/t-SNE)** | Explore socioeconomic groupings | ![](dashboards/screenshots/cluster_tsne.png) |
| **4. Housing & Transport** | Compare WFH vs flats, metro use | ![](dashboards/screenshots/gender_transport.png) |

---

## 📊 Data Pipeline & Methodology

```mermaid
graph TD
    A[Census Data 2011/2021] --> B[Data Cleaning (pandas)]
    B --> C[Feature Engineering]
    C --> D[Delta Metrics (2011–2021)]
    D --> E[PCA & t-SNE (sklearn)]
    C --> F[Bayesian Regression (PyMC3)]
    E --> G[Tableau Visuals]
    F --> G

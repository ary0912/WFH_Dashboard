<h1 align="center">
  💻📊 WFH Socio-Economic Visual Analytics Dashboard (UK: 2011–2030) 🏙️
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/status-Completed-brightgreen" />
  <img src="https://img.shields.io/badge/made%20with-Python%20%26%20Tableau-blue" />
  <img src="https://img.shields.io/badge/license-MIT-yellow" />
</p>

---

## 🧠 Overview

This project explores how **socio-economic and geographical factors** influenced the **Work From Home (WFH)** trends across **33,000+ neighborhoods (LSOAs)** in **England and Wales** using **Census data (2011, 2021)** and predictive modeling for **2030**.

We applied **dimensionality reduction (PCA, t-SNE)** and **Bayesian Linear Regression** to discover patterns and forecast the future. All findings are brought to life through **interactive Tableau dashboards** and **Python-based preprocessing pipelines**.

---

## 🗂️ Key Features

🔹 **Temporal Analysis** — Compare WFH rates from 2011, 2021, and forecast 2030  
🔹 **Geo-Spatial Insights** — Interactive maps highlight WFH disparities  
🔹 **PCA & t-SNE Clustering** — Discover hidden socio-economic patterns  
🔹 **Bayesian Regression** — Predict WFH uptake with uncertainty bounds  
🔹 **Dynamic Visual Storytelling** — Built for policymakers, researchers, and planners  

<p align="center">
  <img src="dashboards/screenshots/map_dashboard.gif" width="90%" />
</p>

---

## 📊 Tableau Dashboards Preview

| Dashboard | Focus Area | Preview |
|----------|------------|---------|
| **Geo WFH Trends** | WFH change by LSOA (2011–2021) | ![Geo](dashboards/screenshots/geo_dashboard.png) |
| **Time Series Forecast** | WFH trend: 2011 → 2021 → 2030 | ![Line](dashboards/screenshots/timeline_forecast.png) |
| **Cluster View (PCA / t-SNE)** | Visualizing latent socio-economic clusters | ![Cluster](dashboards/screenshots/cluster_tsne.png) |
| **Gender / Transport Analysis** | Relationship of gender, housing, commute | ![Scatter](dashboards/screenshots/gender_transport.png) |

---

## 🧬 Tech Stack

### 📦 Python
- `pandas`, `scikit-learn`, `seaborn`
- `PyMC3` for Bayesian Regression
- `matplotlib`, `plotly`
- Jupyter Notebook

### 📈 Tableau
- Advanced dashboarding with parameter toggles, filters, KPIs, custom color palettes

---

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/WFH-VisualAnalytics-UK-2011-2030.git
cd WFH-VisualAnalytics-UK-2011-2030
pip install -r requirements.txt

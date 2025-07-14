# LTE 4G Network KPI Anomaly Detection
To detect anomalies in LTE network performance across Gambia for a telecom operator by analyzing a year-long dataset of LTE KPIs. An LLM-based interface allows users to query specific sites and time ranges, triggering a trained anomaly detection model to identify abnormal behavior
## 🚀 Overview
This project presents a comprehensive Anomaly Detection System for LTE 4G network KPIs, designed to identify abnormal network behaviors at the cell and site level. Leveraging advanced machine learning and time series analysis, our solution enables telecom operators to proactively detect, visualize, and interpret anomalies—leading to better network reliability and improved customer experience.

## 📈 Features
### -**Hybrid Anomaly Detection Models**:
STL+Z-score, Prophet, Isolation Forest, LOF, LSTM/Bi-LSTM, Autoencoder, and ensemble fusion approaches.

### -**Feature Engineering**:
Includes lagged features, rolling statistics, and temporal patterns for enhanced model accuracy.

### -Geo-Spatial Analysis:
Interactive map-based visualization of network sites, anomaly clusters, and KPI trends.

### -LLM-based Reports:
Automated anomaly summaries and actionable insights using Large Language Models.

### -Streamlit Web App:
User-friendly interface for data exploration, anomaly detection, visualization, and reporting.

## 🧑‍💻 Project Modules
### 1.Data Preprocessing & Cleaning:
Handling missing values, filtering outliers, normalizing KPIs.

### 2.Feature Engineering:
Extracting temporal, rolling, and trend-based features from raw KPIs.

### 3.Modeling & Detection:
Training and evaluating multiple ML/DL/statistical models, including fusion methods for robust results.

### 4.Geo-Search Module:
Cluster and filter anomalies spatially using site metadata and frequency band information.

### 5.LLM Summary Function:
Automated generation of business-oriented anomaly reports and technical recommendations.

### 6.Web Application:
Streamlit-based dashboard for interactive use by network engineers and business users.

## 🏗️ How It Works
### 1.Prepare Data:

Upload and clean LTE KPI datasets and metadata.

### 2.Feature Engineering:

Generate lagged, rolling, and trend features for each cell and KPI.

### 3.Anomaly Detection:

Apply and compare hybrid models (statistical, ML, DL, ensemble voting).

### 4.Geo-Spatial Visualization:

Map and analyze anomalies by region, site, cell, and frequency band.

### 5.LLM-Based Reporting:

Generate interpretive summaries and business insights.

# 📊 Tools & Technologies
# *Languages: Python
# *ML/Stats: Prophet, STL, LOF, Autoencoder, Bi-LSTM
# *Visualization: Matplotlib, Plotly, Folium
# *UI: Streamlit
# *Others: Pandas, NumPy, Scikit-learn, TQDM




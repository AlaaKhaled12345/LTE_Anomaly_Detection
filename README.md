# LTE 4G Network KPI Anomaly Detection
To detect anomalies in LTE network performance across Gambia for a telecom operator by analyzing a year-long dataset of LTE KPIs. An LLM-based interface allows users to query specific sites and time ranges, triggering a trained anomaly detection model to identify abnormal behavior
## 🚀 Overview
This project presents a comprehensive Anomaly Detection System for LTE 4G network KPIs, designed to identify abnormal network behaviors at the cell and site level. Leveraging advanced machine learning and time series analysis, our solution enables telecom operators to proactively detect, visualize, and interpret anomalies—leading to better network reliability and improved customer experience.

<img width="1783" height="617" alt="image" src="https://github.com/user-attachments/assets/9eedd3ad-890c-4687-946b-f373f1d2a291" />


## 📈 Features
 - **Hybrid Anomaly Detection Models:**
   
   STL+Z-score, Prophet, Isolation Forest, LOF, LSTM/Bi-LSTM, Autoencoder, and ensemble fusion approaches.

 - **Feature Engineering:**
   
   Includes lagged features, rolling statistics, and temporal patterns for enhanced model accuracy.

 - **Geo-Spatial Analysis:**
   
   Interactive map-based visualization of network sites, anomaly clusters, and KPI trends.
 
 - **LLM-based Reports:**
   
   Automated anomaly summaries and actionable insights using Large Language Models.

- **Streamlit Web App:**
  
   User-friendly interface for data exploration, anomaly detection, visualization, and reporting.

## 🧑‍💻 Project Modules
### 1.Data Preprocessing & Cleaning:
Handling missing values, filtering outliers, normalizing KPIs.

<img width="1879" height="676" alt="image" src="https://github.com/user-attachments/assets/8834e828-4006-4757-ab58-f47076893116" />


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

<img width="679" height="707" alt="image" src="https://github.com/user-attachments/assets/7a0da83e-fe9c-4403-90f5-d4939b427eec" />


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

## 📊 Example Results for Anomaly Detection module ( Prophet (60%) + STL + Z-score (40%) )

<img width="1755" height="402" alt="image" src="https://github.com/user-attachments/assets/bcb40f75-eb19-4ab3-9d4f-194a31c547ac" />


<img width="1755" height="347" alt="image" src="https://github.com/user-attachments/assets/a6de1a4f-09cf-48cd-965e-ac7c6d1de069" />




## 📊 Tools & Technologies
- **Languages:** Python
- **ML/Stats:** Prophet, STL, LOF, Autoencoder, Bi-LSTM
- **Visualization:** Matplotlib, Plotly, Folium
- **UI:** Streamlit
- **Others:** Pandas, NumPy, Scikit-learn, TQDM

## 📄 Documentation

- [**LTE_Anomaly.pdf**](https://github.com/AlaaKhaled12345/LTE_Anomaly_Detection/blob/main/LTE_Anomaly.pdf):
  
  Complete guide covering project approach, modeling details, and results.

- [**Graduation_Presentation.pptx**](https://github.com/AlaaKhaled12345/LTE_Anomaly_Detection/blob/main/Graduation_Presentation.pptx):  
  Visual summary for business and technical audiences.



## 👩‍💼 Business Impact
- **Proactive network health monitoring**

- **Reduced mean-time-to-repair (MTTR)**

- **Actionable insights for engineers and managers**

- **Adaptable to other telco environments or KPIs**

## 👏 Acknowledgments
- **Supervisors:**
Dr. Mahmoud Abdel Aziz, Eng. Meriham Rizk

- **Special Thanks:**
The Information Technology Institute (ITI) and everyone who supported this work

## 📫 Contact
*Alaa Khaled Samir* [Email Me](alaa.khaled18201@gmail.com) | [LinkedIn](www.linkedin.com/in/alaa-khaled18) | [GitHub](https://github.com/AlaaKhaled12345)

*Marwa Shaaban Abd Elhakim* [Email Me](marwaashaaban99@icloud.com) | [LinkedIn](https://www.linkedin.com/in/marwa-shaaban-abd-elhakim/) | [GitHub](https://github.com/Marwa-Shaaban)

## 🏷️ Keywords
LTE 4G Anomaly Detection Telecom Time Series Machine Learning Deep Learning KPI Streamlit Geo-Spatial LLM Python





# Weather Trend Forecasting - Technical Assessment

## 📌 Project Overview
This project aims to analyze and forecast global weather trends using the **Global Weather Repository** dataset. The dataset contains over 40 features related to daily weather conditions across different locations worldwide. The goal is to implement data preprocessing, exploratory data analysis (EDA), various forecasting models, anomaly detection, and climate pattern analysis to derive meaningful insights.

## 🚀 PM Accelerator Mission
> By making industry-leading tools and education available to individuals from all backgrounds, we level the playing field for future PM leaders. This is the PM Accelerator motto, as we grant aspiring and experienced PMs what they need most – Access. We introduce you to industry leaders, surround you with the right PM ecosystem, and discover the new world of AI product management skills.

## 📂 Dataset
- **Source:** Kaggle ([Global Weather Repository](https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository/code))
- **Features:**
  - Temperature (Min, Max, Mean)
  - Precipitation levels
  - Wind speed and direction
  - Air quality parameters (PM2.5, CO, NO2)
  - Humidity and dew point
  - Atmospheric pressure
  - Timestamp (last updated)

## 🔬 Methodology
### 1️⃣ Data Cleaning & Preprocessing
- **Handling Missing Values:**
  - Median/mode imputation for numerical & categorical features.
  - Forward-fill and backward-fill techniques for time-series gaps.
- **Outlier Detection & Treatment:**
  - Used Isolation Forest and IQR methods.
- **Feature Engineering:**
  - Created derived variables like Temperature Difference, Wind Chill Factor.
  - Added Seasonal Indicators (Winter, Summer, Monsoon).
- **Normalization & Encoding:**
  - Scaled numerical features using MinMaxScaler.
  - One-Hot Encoding and Label Encoding for categorical features.

### 2️⃣ Exploratory Data Analysis (EDA)
- **Trend Analysis:** Patterns in temperature, humidity, and precipitation over time.
- **Correlation Analysis:** Examined relationships between weather parameters.
- **Visualizations:**
  - 📊 Time series plots for temperature and precipitation trends.
  - 🔥 Correlation heatmaps.
  - 🌍 Geospatial maps for weather variations.
  - 📉 Histograms and box plots for distribution insights.
  - 
## EDA visualizations:

![feature_importance_unique](https://github.com/user-attachments/assets/8fb49f66-ffe7-4719-8b5e-020b1d328b98)
![EDA3](https://github.com/user-attachments/assets/e3a9a7b5-ae23-40da-ba27-14516fc7d4ef)
![EDA2](https://github.com/user-attachments/assets/86a6dd79-f540-43ff-af7e-b605499fd59d)
![EDA1](https://github.com/user-attachments/assets/40bcdc47-8005-456c-b9c4-287a07fa7fa3)
![anomaly_detection](https://github.com/user-attachments/assets/fcfc408f-67ba-4ac1-8530-4faf5921c45c)
![air_quality2](https://github.com/user-attachments/assets/e9b104c0-60f7-45c3-9698-0c680d29177f)
![air_quality](https://github.com/user-attachments/assets/7cb2762f-2161-45d9-9954-081f122de8d9)


### 3️⃣ Forecasting Models
- **Model Implementation:**
  - **📈 ARIMA:** Captures time-series dependencies.
  - **📊 Facebook Prophet:** Handles seasonality & holiday effects.
  - **🌳 Random Forest Regression:** For non-linear relationships.
  - **🤖 Ensemble Model:** Combines forecasts for higher accuracy.
- **Evaluation Metrics:**
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - R² Score
 
## Forecasting visualizations:

![temporal_analysis2](https://github.com/user-attachments/assets/8ec255f8-fd0d-4af0-b5b7-bf1c76fb0f5c)
![temporal_analysis](https://github.com/user-attachments/assets/8768a192-e63c-4533-96ec-6c963ae6b114)
![temp2](https://github.com/user-attachments/assets/1d1110da-4416-44b3-8f23-70fe8a4e0350)
![temp_distribution](https://github.com/user-attachments/assets/d776d744-58be-4dcf-87d5-2e4786de20b9)
![temp_by_latitude](https://github.com/user-attachments/assets/715921ae-ad8d-47b7-a8c9-bbcd5468d6ff)
![temp_by_continent](https://github.com/user-attachments/assets/e44b6c23-bbb6-4ceb-b7ac-3c4a6b40a578)
![scatter_unique](https://github.com/user-attachments/assets/62268f4c-2a64-4f6e-85bf-c888f39584b9)
![random_forest2](https://github.com/user-attachments/assets/2259cf1e-a713-4539-b69a-ea05039f1206)
![random_forest](https://github.com/user-attachments/assets/7501dcb1-13bb-4a11-8fff-748c445575be)
![random_forest_feature_imp](https://github.com/user-attachments/assets/93295a73-fa69-4a33-a8b1-6fbf9b521858)


### 4️⃣ Advanced Analysis
- **🔍 Anomaly Detection:**
  - Isolation Forest for extreme temperature and precipitation anomalies.
  - DBSCAN clustering for spatial anomaly detection.
- **🌎 Climate Pattern Analysis:**
  - Long-term temperature trends and urban heat island effects.
  - Seasonal shifts using historical data.
- **💨 Air Quality & Weather Correlation:**
  - PM2.5 levels, wind speed, and humidity correlation analysis.
  - High-risk pollution period identification.
- **🗺️ Geospatial Analysis:**
  - Heatmaps for precipitation density & drought-prone areas.
  - Regional temperature and humidity variations.
 
## Unique Analysis vidualizations:

![unique_scatter](https://github.com/user-attachments/assets/6340843e-5042-45b8-a93c-222f4038cd0c)
![unique_heat_map](https://github.com/user-attachments/assets/e33860ad-d72f-48dc-be12-bc3812c94cf7)
![unique_air_quality2](https://github.com/user-attachments/assets/7fc998e2-482b-4968-b45e-c750e6b23a04)
![unique_air_quality](https://github.com/user-attachments/assets/a7fd4ae5-aae8-4c28-9bc8-08487fc7620c)



## 📊 Results & Key Findings
✅ Temperature trends indicate global warming indicators with regional variations.  
✅ Precipitation patterns show increasing unpredictability.  
✅ Ensemble models outperformed single forecasting models.  
✅ Wind speed significantly affects air quality dispersion.  
✅ Anomalies in extreme weather events align with climate change patterns.  

## 🔮 Future Work
🔹 Implement deep learning models (LSTM, GRU) for improved forecasting accuracy.  
🔹 Integrate real-time weather data streaming using APIs.  
🔹 Enhance anomaly detection using reinforcement learning techniques.  
🔹 Extend geospatial analysis using satellite imagery for better climate modeling.  

## 📁 Project Repository Structure
```
├── data/                    # Processed dataset files
├── notebooks/               # Jupyter Notebook with analysis & models
├── results/                 # Model evaluations & visualization outputs
├── README.md                # Project documentation
└── report.pdf               # Final assessment report
```

## ⚙️ How to Run the Project
1️⃣ Clone the repository:
```sh
   git clone <repository_link>
   cd weather-forecasting-project
```
2️⃣  Open the Jupyter Notebook and execute all cells:
```sh
   jupyter notebook PMA_technical_assessment_Prajwal.ipynb
```
4️⃣ View the final report for insights and findings.

## 📌 Submission Details
- **GitHub Repository:** [https://github.com/Prajwal111299/PM_Accelerator_technical_assessment/tree/master]
- **Includes:**
  - 📜 Jupyter Notebook
  - 📊 Processed dataset (if shareable)
  - 📈 Model results & visualizations
  - 📄 README.md & Final Report

---

## 👨‍💻 Author: **Prajwal Kumar**  
**📅 Date:** April 2025  
**🏫 Affiliation:** Carnegie Mellon University  


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
2️⃣ Install dependencies:
```sh
   pip install -r requirements.txt
```
3️⃣ Open the Jupyter Notebook and execute all cells:
```sh
   jupyter notebook PMA_technical_assessment_Prajwal.ipynb
```
4️⃣ View the final report for insights and findings.

## 📌 Submission Details
- **GitHub Repository:** [Insert Link]
- **Includes:**
  - 📜 Jupyter Notebook
  - 📊 Processed dataset (if shareable)
  - 📈 Model results & visualizations
  - 📄 README.md & Final Report

---

## 👨‍💻 Author: **Prajwal Kumar**  
**📅 Date:** April 2025  
**🏫 Affiliation:** Carnegie Mellon University  


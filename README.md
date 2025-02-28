# 🌍 Cooling Urban Heat Islands – EY Open Science AI Data Challenge 2025  

This project is part of the **2025 EY Open Science AI & Data Challenge**, focusing on **predicting Urban Heat Islands (UHI) using AI & satellite data**.  
The goal is to develop an **open-source machine learning model** to analyze **temperature variations, urban density, and climate factors** affecting heat distribution in cities.  

---

## 📌 Project Overview  
Urban Heat Islands (UHIs) result in **temperature variations exceeding 10°C**, affecting public health, energy consumption, and sustainability.  
This project leverages **machine learning & AI** to analyze ground-level temperature data, satellite imagery, and weather patterns to:  
✔ Predict UHI hotspots at a **micro-scale resolution**.  
✔ Identify key factors contributing to urban heating.  
✔ Provide insights for **urban planners & policymakers** to design sustainable cooling strategies.  

---

## 🛰️ Datasets Used  
The model integrates multiple datasets to predict UHI severity:  

✅ **Ground-Based Air Temperature Data** – Collected via automobile traverses in NYC, providing **11,229 data points**.  
✅ **Building Footprint Data** – Mapping urban density and its impact on heat retention.  
✅ **Sentinel-2 Optical Satellite Data** – Providing **multispectral imaging** for vegetation & land surface monitoring.  
✅ **Landsat Thermal Infrared Data** – Measuring **Land Surface Temperature (LST)** variations.  
✅ **Local Weather Data** – Including **temperature, wind speed, humidity, and solar flux** for climate impact analysis.  

---

## 🏗️ Project Architecture  
The project workflow follows these key steps:  

1️⃣ **Data Preprocessing & Cleaning** – Using Python (Pandas, NumPy) to clean & standardize temperature, weather, and satellite datasets.  
2️⃣ **Feature Engineering** – Extracting vegetation indices, land cover patterns, and atmospheric conditions.  
3️⃣ **Machine Learning Model Development** – Training **regression & deep learning models (XGBoost, TensorFlow, Scikit-learn)**.  
4️⃣ **Model Evaluation & Hyperparameter Tuning** – Using **GridSearchCV & cross-validation** to optimize accuracy.  
5️⃣ **Visualization & Insights** – Deploying **Power BI & Tableau** dashboards for interactive UHI heatmaps.  

---

## 🚀 Tech Stack  
📌 **Programming:** Python (Pandas, NumPy, Scikit-learn, TensorFlow)  
📌 **Data Storage & Processing:** SQL, Snowflake  
📌 **Satellite Data Handling:** Google Earth Engine, OpenCV  
📌 **Visualization:** Tableau, Power BI, Matplotlib, Seaborn  

---

## 🔬 Key Insights  
✔ **High-density urban areas retain significantly more heat**, especially with reduced vegetation.  
✔ **Wind speed & water proximity** strongly impact heat dispersion.  
✔ **Deep learning models outperform traditional regression** for micro-scale UHI predictions.  
✔ **Optimal cooling strategies** involve increasing urban greenery and reflective roofing materials.  

---

## 🏆 Challenge Impact
This project contributes to urban sustainability & climate adaptation by:

✅ Providing high-resolution UHI predictions for city planners.
✅ Optimizing energy-efficient urban design using AI.
✅ Promoting open-source climate research through EY's Open Science Initiative.

---

## 📌 References
📖 2025 EY Open Science AI Data Challenge Guide
📍 NASA Landsat & Sentinel-2 Data – USGS Earth Explorer
📍 Urban Heat Island Research – IPCC Climate Reports

---

📢 For questions or contributions, feel free to open an issue or submit a pull request! 🚀

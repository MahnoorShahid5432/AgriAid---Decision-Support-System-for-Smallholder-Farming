# 🌾 AgriAid: AI Assistant for Smarter Farming

AgriAid is a multilingual, AI-powered assistant that provides smallholder farmers with real-time, location-specific crop recommendations and yield predictions. By integrating satellite-based weather, soil, and historical yield data, AgriAid empowers farmers to make data-driven decisions that improve planning, reduce risk, and boost crop productivity.

📁 [Access Full Code, Notebooks & Data](https://drive.google.com/drive/folders/1R9caIbzLSzw0z4uTCExyvy2cVN-kREpC?usp=sharing)

---

## Key Features

- **📍 Geo-based Crop Recommender**  
  Suggests top 3 most profitable crops to grow based on user-entered latitude & longitude.

- **📈 Yield Prediction**  
  Uses machine learning (XGBoost, TabNet, FNN) to forecast crop yield based on environmental conditions.

- **🌦️ Weather Forecasting**  
  Implements Prophet to forecast rainfall and temperature trends at the farm level.

- **🧪 Soil & Climate Analysis**  
  Processes satellite data (SoilGrids, ERA5) using PySpark to extract agro-climatic features globally.

- **🗣️ Conversational Agent (Prototype)**  
  Supports multilingual input to improve accessibility for low-tech, rural users.

---

## Tech Stack

- **Languages & Tools**: Python, PySpark, Pandas, Rasterio, XGBoost, TabNet, Prophet, Matplotlib
- **Data Sources**: SoilGrids, ERA5, SPAM, NASA POWER, OpenWeather
- **Infrastructure**: Google Colab, Jupyter Notebooks

---

## Notebooks

| Task | Notebook |
|------|----------|
| Data Processing | `Data_Processing.ipynb` |
| Model Training (Global) | `Training_Global.ipynb` |
| MVP Yield Prediction | `MVP_yield_prediction.ipynb` |
| Rain Prediction | `MVP_Weather&Rain.ipynb` |
| UI Development | `UI.ipynb` |

---

## Model Results

- **XGBoost**:  
  RMSE = 11,113 | R² = 0.801 (Best performance)

- **TabNet**:  
  RMSE = 14,833 | R² = 0.646

---

## Business Impact

- Expected to improve crop yield by **10–20%** for adopting farmers  
- Personalized recommendations improve **decision confidence** and reduce risk  
- Optimized for low-connectivity, multilingual regions to improve accessibility

---

## 👨‍🌾 Team

Mahnoor Shahid · Avi Reissberg · Siyi (Susie) Zhang · Tingwei (Elsiey) Hu · Peilu Han

📎 [Project Report PDF](https://drive.google.com/file/d/17bf758Z7McCfZKNwxxMayalKi57f1vHo/view?usp=sharing)

---

*For reproducibility, all datasets, trained models, and pipeline scripts are shared in the Drive folder linked above.*

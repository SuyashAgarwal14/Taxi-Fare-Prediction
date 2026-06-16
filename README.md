# 🚖 Taxi Fare Prediction

## 📌 Project Overview
The **Taxi Fare Prediction** project is a Machine Learning application designed to accurately predict taxi fares within New York City based on trip parameters. By leveraging historical trip data, the system performs robust data cleaning, feature engineering, and predictive modeling using XGBoost. Additionally, the project features a real-time prediction GUI built with Tkinter, complete with interactive route visualization using Folium.

## 🚀 Key Features
* **Exploratory Data Analysis (EDA):** Comprehensive visualizations identifying fare distribution patterns, trip counts, and key pickup/dropoff zones across NYC.
* **Robust Data Processing:** Filtering of geographical anomalies, removal of invalid passenger counts, and baseline fare enforcement.
* **Advanced Feature Engineering:** Extraction of temporal features (`pickup_day`, `pickup_hour`, `pickup_month`, `pickup_day_of_week`, etc.) from raw timestamps, alongside GPS coordinate utilization.
* **High-Accuracy ML Model:** Utilizes an optimized XGBoost regression model to deliver reliable fare estimates.
* **Interactive GUI:** A user-friendly desktop application (Tkinter) that predicts fares in real-time and maps the exact route (Folium).

## 🛠️ Tech Stack & Tools
* **Programming Language:** Python 3.x
* **Data Processing & EDA:** Pandas, NumPy, Matplotlib, Seaborn
* **Machine Learning:** XGBoost, Scikit-Learn
* **Application Interface:** Tkinter, TkinterMapView
* **Mapping & Visualization:** Folium

## 📊 Dataset Insights
The dataset contains historical NYC taxi trip records. Key attributes include:
* `pickup_datetime`: Timestamp of trip initiation.
* `pickup_longitude` / `pickup_latitude`: Starting GPS coordinates.
* `dropoff_longitude` / `dropoff_latitude`: Ending GPS coordinates.
* `passenger_count`: Number of passengers.
* `fare_amount`: Target variable (Total fare cost).

### Data Cleaning Steps Applied:
1. Removed invalid coordinates outside the logical NYC bounding box.
2. Filtered out trips with `0` passengers.
3. Removed records with base fare anomalies (fares `< $2.50`).

## 📈 Model Performance
The XGBoost model was evaluated against standard regression metrics, achieving high predictive reliability:
* **R² Score:** 0.82
* **RMSE (Root Mean Squared Error):** 3.9
* **MAE (Mean Absolute Error):** 1.76

## 💻 Installation & Usage

### 1. Clone the Repository
```bash
git clone [https://github.com/yourusername/taxi-fare-prediction.git](https://github.com/yourusername/taxi-fare-prediction.git)
cd taxi-fare-prediction# 🚖 Taxi Fare Prediction

## 📌 Project Overview
The **Taxi Fare Prediction** project is a Machine Learning application designed to accurately predict taxi fares within New York City based on trip parameters. By leveraging historical trip data, the system performs robust data cleaning, feature engineering, and predictive modeling using XGBoost. Additionally, the project features a real-time prediction GUI built with Tkinter, complete with interactive route visualization using Folium.

## 🚀 Key Features
* **Exploratory Data Analysis (EDA):** Comprehensive visualizations identifying fare distribution patterns, trip counts, and key pickup/dropoff zones across NYC.
* **Robust Data Processing:** Filtering of geographical anomalies, removal of invalid passenger counts, and baseline fare enforcement.
* **Advanced Feature Engineering:** Extraction of temporal features (`pickup_day`, `pickup_hour`, `pickup_month`, `pickup_day_of_week`, etc.) from raw timestamps, alongside GPS coordinate utilization.
* **High-Accuracy ML Model:** Utilizes an optimized XGBoost regression model to deliver reliable fare estimates.
* **Interactive GUI:** A user-friendly desktop application (Tkinter) that predicts fares in real-time and maps the exact route (Folium).

## 🛠️ Tech Stack & Tools
* **Programming Language:** Python 3.x
* **Data Processing & EDA:** Pandas, NumPy, Matplotlib, Seaborn
* **Machine Learning:** XGBoost, Scikit-Learn
* **Application Interface:** Tkinter, TkinterMapView
* **Mapping & Visualization:** Folium

## 📊 Dataset Insights
The dataset contains historical NYC taxi trip records. Key attributes include:
* `pickup_datetime`: Timestamp of trip initiation.
* `pickup_longitude` / `pickup_latitude`: Starting GPS coordinates.
* `dropoff_longitude` / `dropoff_latitude`: Ending GPS coordinates.
* `passenger_count`: Number of passengers.
* `fare_amount`: Target variable (Total fare cost).

### Data Cleaning Steps Applied:
1. Removed invalid coordinates outside the logical NYC bounding box.
2. Filtered out trips with `0` passengers.
3. Removed records with base fare anomalies (fares `< $2.50`).

## 📈 Model Performance
The XGBoost model was evaluated against standard regression metrics, achieving high predictive reliability:
* **R² Score:** 0.82
* **RMSE (Root Mean Squared Error):** 3.9
* **MAE (Mean Absolute Error):** 1.76

## 💻 Installation & Usage

### 1. Clone the Repository
```bash
git clone [https://github.com/yourusername/taxi-fare-prediction.git](https://github.com/yourusername/taxi-fare-prediction.git)
cd taxi-fare-prediction

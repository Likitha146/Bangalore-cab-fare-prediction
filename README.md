# Bangalore-cab-fare-prediction
🚖 Bangalore Cab Fare Prediction (Machine Learning + Geospatial Analytics)

This project predicts cab fare prices in Bangalore using Machine Learning and Geospatial Feature Engineering.
It includes distance calculations, interactive route maps using Folium, and ML models such as Linear Regression, Random Forest, and XGBoost.

🔥 Features

Predict cab fare based on location, distance, and time

Geospatial feature engineering (Haversine & Geodesic Distance)

Interactive route maps using Folium

Polyline route decoding

Time-based features (hour, day, month)

Multiple ML models trained and evaluated

Full data cleaning & preprocessing pipeline

🧰 Tech Stack

Python

Pandas, NumPy

Scikit-Learn

XGBoost

GeoPy

Folium (maps)

Matplotlib, Seaborn

Jupyter Notebook / Google Colab

📂 Dataset Information

The dataset contains:

Pickup Latitude & Longitude

Drop Latitude & Longitude

Passenger Count

Date & Time of Ride

Fare Amount (target variable)

⚙️ Project Workflow

Load & explore dataset

Handle missing / invalid values

Validate GPS coordinates

Feature Engineering

Haversine Distance

Geodesic Distance

Time Features (hour, day, month)

Visualize routes using Folium maps

Train ML models:

Linear Regression

Random Forest

XGBoost

Evaluate using RMSE, MAE, R²

Predict final fare

📦 Installation
git clone https://github.com/your-username/bangalore-cab-fare-prediction.git
cd bangalore-cab-fare-prediction
pip install -r requirements.txt

▶️ How to Run
1. Open cab_fare_prediction.ipynb
2. Run all cells in order
3. View prediction results & maps inside the notebook

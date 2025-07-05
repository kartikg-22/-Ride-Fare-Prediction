# 🚖 Ride Fare Prediction Using Deep Learning  
**Integrating Weather and Temporal Dynamics**

This project aims to accurately predict ride fares for services like Uber and Lyft by integrating traditional ride attributes with real-world weather and time-based features. Unlike basic estimators that rely only on distance or duration, this approach captures dynamic pricing patterns caused by environmental and temporal factors.

## 🔍 Key Highlights

- **Objective:** Predict dynamic ride fares using machine learning by incorporating weather conditions and temporal data alongside trip details.
- **Features Used:**
  - **Ride Details:** Distance, Cab Type, Fare per Mile
  - **Weather:** Temperature, Rain, Wind Speed, Cloud Cover
  - **Temporal:** Hour of Day, Weekend Flag, Holiday Indicator, Peak Hour

- **Machine Learning Models Applied:**
  - Gradient Boosting Regressor ✅ *(Best Performer)*
  - Random Forest Regressor
  - Linear Regression

- **Performance (on combined dataset):**
  - **Gradient Boosting Regressor**
    - R² Score: **0.94**
    - Mean Squared Error (MSE): **2.98**
    - Mean Absolute Error (MAE): **1.45**

## 🛠️ Tools & Technologies

- **Languages & Libraries:** Python, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
- **Data Sources:** Uber/Lyft ride data, Weather data (via APIs), Time-based derived features


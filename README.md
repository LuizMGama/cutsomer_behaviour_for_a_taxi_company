# 🚕 Project: Customer Behavior Forecasting for a Taxi Company

## 🎯 Project Objective  
The objective of this project is to help the taxi company **Sweet Lift Taxi** forecast the number of ride requests for the next hour in order to optimize driver availability during peak times. A supervised machine learning model was developed to predict hourly demand using historical data.

---

## ✅ Results Achieved  
- Resampled time series data into one-hour intervals  
- Conducted exploratory data analysis and visualized seasonal patterns and trends  
- Built lag-based features to capture temporal dependencies  
- Split data chronologically into training and testing sets (90% / 10%)  
- Trained and evaluated multiple regression models including:
  - **Linear Regression**
  - **Ridge and Lasso Regression**
  - **Random Forest**
  - **CatBoost**  
- The best-performing model achieved **RMSE below 48** on the test set, successfully meeting the project's requirement

---

## 🛠️ Tools and Technologies Used  
- **Language:** Python  
- **Main libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels, CatBoost  
- **Techniques and concepts:**
  - Time series resampling
  - Lag feature engineering
  - Train-test split preserving temporal order
  - Hyperparameter tuning with `GridSearchCV`
  - Error evaluation using `RMSE`

---

## 🚀 Skills Developed  
- Handling and transforming time series data  
- Building lag-based features for temporal prediction  
- Comparing regression models using consistent metrics  
- Visualizing trends and seasonality in hourly data  
- Framing business problems into predictive modeling pipelines

---

## 🔧 Future Improvements  
- Incorporate external variables such as weather or events  
- Automate model retraining for ongoing use in production  
- Deploy model with live data pipeline integration  
- Develop a real-time dashboard to monitor predictions and demand

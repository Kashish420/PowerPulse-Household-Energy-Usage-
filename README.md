
## PowerPulse – Household Energy Usage Forecast

### Overview

PowerPulse is a data science project focused on predicting household energy consumption using time-series data. By applying various regression models and feature engineering techniques, this project aims to help understand and forecast daily electricity usage patterns.

### Objectives

* Analyze patterns in household energy usage.
* Engineer time-based and weather-related features.
* Train and evaluate multiple regression models for forecasting.
* Identify the best-performing model using RMSE, MAE, and R² metrics.
* Provide interpretability through SHAP analysis.

### Dataset

* **Source**: UCI Machine Learning Repository.
* **Details**: The dataset contains readings of electric power consumption in one household, measured over several years.

### Key Techniques

* Time-series feature engineering (hour, weekday, month, etc.).
* Machine learning models: Linear Regression, Decision Tree, Random Forest, XGBoost, Gradient Boosting.
* Model evaluation using RMSE, MAE, and R².
* SHAP for feature importance and interpretability.

### Tools Used

* Python (Pandas, NumPy, Scikit-learn, XGBoost, SHAP)
* Jupyter/Colab for code execution and visualization

### Results

* Gradient Boosting delivered the most accurate energy usage predictions.
* SHAP plots revealed that temperature, time of day, and humidity significantly impact energy consumption.

### Conclusion

PowerPulse demonstrates how machine learning can be effectively used to forecast household energy needs. These insights can guide energy-saving decisions and improve load planning.

---

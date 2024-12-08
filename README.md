# Bike-sharing-ML-project-Submission
Bike-Sharing ML Project Submission
# Project Overview
This project aims to predict bike demand in Seoul using machine learning techniques. The objective is to enable better management of bike-sharing systems by accurately forecasting user demand based on various factors, including weather, time, and seasonal trends.

# Dataset
Dataset Name: SeoulBikeData.csv
The dataset contains information on hourly bike rentals in Seoul along with attributes such as date, weather conditions, temperature, and holidays.

# Key features include:

Date: The specific day of observation.
Hour: The hour of the day.
Temperature (°C): The recorded temperature during the hour.
Humidity (%): Percentage of humidity.
Dew Point Temperature (°C): Calculated dew point.
Wind Speed (m/s): Wind conditions during the hour.
Visibility (10m): Distance of visibility.
Rainfall (mm): Precipitation during the hour.
Snowfall (cm): Snow accumulation during the hour.
Holiday: Whether the day was a holiday.
Season: Categorization into seasons.
Methodology
## Steps Taken:
### Data Preprocessing:

Handling missing values and outliers.
Feature encoding for categorical variables.
Scaling and normalizing numerical features.
Exploratory Data Analysis (EDA):

Analyzed the relationship between bike demand and weather, season, and time.
Visualized trends using colorful and informative plots.
# Feature Engineering:

Generated additional features like day-of-week and time-of-day segments.
Addressed multicollinearity between features, e.g., temperature and dew point temperature.
Model Building and Evaluation:

# Experimented with various models:
Linear Regression
Decision Tree
Random Forest
Gradient Boosting
Extreme Gradient Boosting (XGBoost)
Best Performance: XGBoost achieved 98% accuracy on the training set and 92% accuracy on the test set.
Hyperparameter Tuning:

Used grid search and random search to optimize model performance.
Performance Metrics:

Evaluated models using RMSE, MAE, and R² scores.
Key Findings
High demand during morning and evening rush hours.
Low demand during winters; peak demand in June.
Removing outliers reduced model accuracy.

# Key libraries:

pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost

#Conclusion
This project demonstrates the power of machine learning in solving real-world problems like predicting bike demand. It highlights the importance of data preprocessing, feature engineering, and model optimization. The insights from this project can guide better management of bike-sharing systems in urban environments.



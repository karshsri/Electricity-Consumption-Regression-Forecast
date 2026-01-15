# Electricity Consumption Regression Forecast

## 📌 Project Overview
This project forecasts daily household electricity consumption using a multiple linear regression model. Lag-based and rolling average features were engineered to capture temporal consumption patterns.

## 🛠️ Technologies Used
- Python
- pandas
- scikit-learn
- matplotlib
- VS Code
- Git & GitHub

## 📂 Dataset
The dataset contains daily household electricity consumption along with household and environmental features:
- Household_ID
- Date
- Energy_Consumption_kWh
- Household_Size
- Avg_Temperature_C
- Has_AC
- Peak_Hours_Usage_kWh

## 🔧 Feature Engineering
- Lag feature: previous day consumption (lag_1)
- Rolling average: 3-day moving average (rolling_3)

## 📈 Model
- Multiple Linear Regression
- Train/Test split (80/20)
- Evaluation metric: Mean Absolute Error (MAE)

## 📊 Results
- Actual vs Predicted comparison
- Residual analysis
- Feature coefficient analysis
- 7-day consumption forecast

Forecast output is saved as:

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

<img width="587" height="609" alt="img4" src="https://github.com/user-attachments/assets/2af960e5-2de6-4090-98ea-7dc21d28aa78" />
<img width="584" height="455" alt="img3" src="https://github.com/user-attachments/assets/fe5d42e6-95e6-42bc-9408-2ec85a9b0f71" />
<img width="565" height="455" alt="img2" src="https://github.com/user-attachments/assets/4c03c847-118e-424b-90cf-0a8d56362225" />
<img width="562" height="455" alt="img1" src="https://github.com/user-attachments/assets/f1c3a805-ad16-4f96-9924-af13a8c5f9c4" />


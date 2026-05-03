# gas-demand-forecasting-ML

comparative analysis of statistical and machine learning models for gas demand forecasting
# Gas Demand Forecasting using Machine Learning and Time Series Models

## 📌 Project Overview
This project aims to forecast gas consumption using both statistical and machine learning approaches.  
A comparative analysis is conducted between classical time series models and advanced ML models.

## 🎯 Objectives
- Analyze gas consumption data
- Apply time series forecasting techniques
- Compare performance of different models
- Identify the most accurate model

## 🧠 Models Used
- SARIMA (Statistical Model)
- XGBoost (Machine Learning)
- CatBoost (Machine Learning)
- prohet+catboost(hybrid model)

## ⚙️ Methodology
- Data preprocessing and cleaning
- Feature engineering (lag features, rolling statistics)
- Train-test split (time series split)
- Model training and evaluation
- time series decomposition using prophet

## 📊 Results
| Model     | R² Score | MAE | RMSE |
|----------|--------|-----|------|
| SARIMA   | 0.9220     0.00030  |  0.00041   |      |
| XGBoost  |   0.5945     |0.00093     | 0.00120     |
| CatBoost+prophet | 0.96   |     |      |

👉 Best model: **Hybrid(prophet+catboost)**

## 🔍 Key Insight
The hybrid approach combining Prophet and CatBoost achieved the best performance.  
Prophet captures trend and seasonality, while CatBoost models the residual errors, improving overall accuracy.

## 📈 Visualization
- Actual vs Predicted values
- Model comparison plots

## 🛠️ Tools & Technologies
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Statsmodels

## 📂 Project Structure

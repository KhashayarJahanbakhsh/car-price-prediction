# car-price-prediction
# 🚗 Car Price Prediction with Machine Learning

This project predicts used car prices based on technical and categorical features such as year, mileage, engine, max power, fuel type, and more.  
I compared multiple regression models and identified the best-performing one.

---

## 📂 Project Structure
- `car_price_comparison.py` → main script for preprocessing, training, and evaluation  
## Overview
This project implements machine learning models to predict car prices based on various features like year, mileage, engine specifications, and more.
The solution includes multiple regression models with performance comparison and feature importance analysis.


---

## ⚙️ Models Compared
- Random Forest Regressor 🌲
- XGBoost Regressor ⚡
- Ridge Regression
- Lasso Regression
- ElasticNet Regression
## Model Performance
After training multiple models, Random Forest achieved the best performance:

| Model         | RMSE (↓)  | R² (↑)  | CV RMSE (↓) |
|---------------|-----------|---------|-------------|
| Random Forest | 137,592   | 0.9711  | 0.223       |
| XGBoost       | 155,900   | 0.9629  | 0.219       |
| Ridge         | 321,616   | 0.8422  | 0.310       |
| ElasticNet    | 407,382   | 0.7468  | 0.327       |
| Lasso         | 453,471   | 0.6863  | 0.354       |

✅ **Conclusion**: Random Forest is the most accurate model for predicting car prices.

## 📊 Results Visualization

### R² Comparison
Higher R² = more variance explained.  
Random Forest again performed best (R² ≈ **0.97**).
In this figure you can see rhe result between Random Foresr and XGBoost very close to each other.
 This bar chart shows the R² score (coefficient of determination) for each model. R² values range from 0 to 1, where:

1 indicates perfect prediction
0 means the model is no better than a horizontal line
Negative values indicate worse performance than a horizontal line
Models are sorted from highest to lowest R² score.

https://github.com/KhashayarJahanbakhsh/car-price-prediction/blob/main/Images/model_r2_comparison.png

### Model RMSE Comparison
 This bar chart compares the Root Mean Squared Error (RMSE) across different models. Lower RMSE values indicate better performance. 
 The models are sorted from best (lowest RMSE) to worst. This visualization helps quickly identify which model performs best at minimizing prediction errors.
 





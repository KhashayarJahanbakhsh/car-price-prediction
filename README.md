# car-price-prediction
# 🚗 Car Price Prediction with Machine Learning

This project predicts used car prices based on technical and categorical features such as year, mileage, engine, max power, fuel type, and more.  
I compared multiple regression models and identified the best-performing one.

---

## 📂 Project Structure
- `car_price_comparison.py` → main script for preprocessing, training, and evaluation  


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





# house-price-prediction
House Price Prediction using Multiple Linear Regression

# 🏠 California House Price Prediction using Multiple Linear Regression

This project predicts the **median house value** of California districts using Multiple Linear Regression. The dataset includes geographical and socio-economic factors related to the housing market.

---

## 📊 Dataset Information
- **Dataset Source**: California Housing Dataset
- **Target Variable**: `median_house_value`

### 📌 Features Used
- longitude
- latitude
- housing_median_age
- total_rooms
- total_bedrooms
- population
- households
- median_income
- ocean_proximity (encoded)

---

## 🧠 Machine Learning Approach
✔ Data Loading & Cleaning  
✔ Exploratory Data Analysis (EDA)  
✔ Feature Encoding (ocean proximity)  
✔ Train-Test Split  
✔ Linear Regression Model Training  
✔ Model Evaluation & Visualization  

---

## 📈 Model Performance
| Metric | Score |
|-------|------|
| R² Score | **0.6364** |
| MAE | **51,404.07** |
| MSE | **4,940,061,925.21** |
| RMSE | **70,285.57** |

> The model explains **63%** of price variance — good baseline but can be improved.

---

## 📌 Visualizations
- Correlation Heatmap  
- Actual vs Predicted Price Scatter Plot  
- Residual Distribution Plot  
- Residual vs Predicted Scatter Plot  

(Add images in an `images/` folder and show here)

---

## 🏗 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🚀 Future Enhancements
- Try advanced models (Random Forest, XGBoost)
- Hyperparameter tuning
- More feature engineering
- Remove multicollinearity among features

---

## ▶️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook ml23.ipynb


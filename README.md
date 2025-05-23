# House Prices - Advanced Regression Techniques

## 📌 Project Overview
This project analyzes the Kaggle competition **"House Prices - Advanced Regression Techniques"**, where the goal is to predict house sale prices based on various features.

The objective is to develop an accurate prediction model using **Machine Learning** and **advanced regression techniques**.

## 📊 Dataset
The dataset consists of **79 explanatory variables** that describe various aspects of a house (e.g., size, location, quality of materials).

- **Training Data**: 1,460 entries with known house prices
- **Test Data**: 1,459 entries without price information
- **Target Variable**: `SalePrice` (house sale price)

## 🛠 Approach
1. **Exploratory Data Analysis (EDA)**
   - Data cleaning and handling missing values
   - Visualizing correlations
   - Identifying relevant features

2. **Feature Engineering**
   - Converting categorical variables to numerical values
   - Scaling and normalization
   - Creating new meaningful features

3. **Model Selection & Training**
   - Linear Regression
   - Ridge & Lasso Regression
   - Random Forest & Gradient Boosting (XGBoost, LightGBM)
   - Hyperparameter tuning

4. **Evaluation & Optimization**
   - Metrics: RMSE (Root Mean Squared Error)
   - Feature Importance Analysis
   - Ensemble techniques for improved prediction accuracy

## 🚀 Results
- Best Model: **CatBoost Regressor**
- Root Mean Squared Error (RMSE): **0.1216142**
Key Features: NEW_TotalSF, OverallQual, GrLivArea, YearBuilt, Fireplaces, OverallCound
  
#<img width="573" alt="house_prices" src="https://github.com/user-attachments/assets/f795712a-5a29-44e5-9b6b-c93e99c8d5a2" />

## 📌 Conclusion & Learnings
- **Feature engineering** has a significant impact on model performance.
- **Regularization techniques** (e.g., Ridge, Lasso) help prevent overfitting.
- Ensemble models like **XGBoost** often provide the best performance.

## 📂 Project Details
- **Tools**: Python, Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, XGBoost
- **Author**: Hossein Izadi



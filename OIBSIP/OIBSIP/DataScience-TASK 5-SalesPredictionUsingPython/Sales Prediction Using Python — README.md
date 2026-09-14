# Sales Prediction Using Python

## 1. Problem

The objective of this project is to build a regression model that predicts **product sales based on advertising spend across TV, Radio, and Newspaper channels**.

## 2. Methodology

The project followed a structured machine learning workflow:

- **Data Cleaning:** Checked for missing values, reviewed descriptive statistics, and removed the redundant index column.
- **Exploratory Data Analysis:** Used pairplots and scatter plots to examine the relationship between advertising spend and sales.
- **Correlation Analysis:** Evaluated the relationship between TV, Radio, Newspaper, and Sales using a correlation heatmap.
- **Model Training:** Trained and compared **Linear Regression** and **Random Forest Regressor** models.
- **Model Evaluation:** Assessed performance using **R² Score, MAE, and RMSE**.
- **Residual Analysis:** Examined prediction errors to determine whether the best model showed systematic patterns.
- **Feature Importance:** Identified which advertising channels contributed most strongly to sales prediction.

## 3. Skills

**Python | Pandas | NumPy | Scikit-learn | Matplotlib | Seaborn | Data Cleaning | Exploratory Data Analysis | Regression Modeling | Model Evaluation | Residual Analysis | Feature Importance**

## 4. Results

The **Random Forest Regressor** was the best-performing model, achieving:

- **R² Score:** 0.982
- **MAE:** 0.492
- **RMSE:** 0.576

In comparison, Linear Regression achieved an **R² score of 0.817**.

The analysis also showed that:

- **TV** had the strongest correlation with sales at **0.75**.
- **Radio** had a moderate positive correlation of **0.58**.
- **Newspaper** had the weakest correlation at **0.23**.
- Random Forest feature importance identified **TV (64.02%)** as the most important predictor, followed by **Radio (35.18%)** and **Newspaper (0.80%)**.
- Residuals were roughly randomly distributed around zero, suggesting that the model's errors were not strongly systematic.

## 5. Conclusion

The analysis shows that **TV advertising has the strongest predictive influence on sales, followed by Radio**, while Newspaper contributes very little to the prediction. The **Random Forest Regressor** provided the most accurate sales predictions and substantially outperformed the Linear Regression baseline.
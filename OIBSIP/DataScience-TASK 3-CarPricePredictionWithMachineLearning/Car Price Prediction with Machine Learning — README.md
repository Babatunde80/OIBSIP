# Car Price Prediction with Machine Learning

## 1. Problem

The objective of this project is to build a machine learning regression model that predicts the **selling price of used cars** based on relevant features such as present price, car age, kilometers driven, fuel type, seller type, transmission, and ownership history.

## 2. Methodology

The project followed a structured machine learning workflow:

- **Data Cleaning & Investigation:** Examined the dataset for missing values, data types, unique values, and descriptive statistics.
- **Feature Engineering:** Created `Car_Age` from the vehicle year and extracted the car brand before selecting relevant features for modeling.
- **Exploratory Data Analysis:** Analyzed selling price distribution and relationships between selling price, fuel type, and car age.
- **Feature Encoding:** Converted categorical variables such as fuel type, seller type, and transmission into numerical values.
- **Model Training:** Trained and compared **Linear Regression** and **Random Forest Regressor** models.
- **Model Evaluation:** Evaluated model performance using **R² Score, MAE, and RMSE**.

## 3. Skills

**Python | Pandas | NumPy | Scikit-learn | Matplotlib | Seaborn | Data Cleaning | Feature Engineering | Exploratory Data Analysis | Regression Modeling | Model Evaluation | Feature Importance**

## 4. Results

The **Random Forest Regressor** was the best-performing model, achieving a **test R² score of 0.981**, compared with **0.837** for Linear Regression.

The Random Forest model also achieved:

- **MAE:** 0.337
- **RMSE:** 0.503

Feature importance analysis showed that **Present Price** was the strongest predictor of selling price, followed by **Car Age** and **Kilometers Driven**.

## 5. Conclusion

The project demonstrates that machine learning can effectively predict used-car selling prices from vehicle characteristics. The **Random Forest Regressor** provided the most accurate predictions, while the analysis identified **Present Price and Car Age** as the most influential factors affecting a vehicle's predicted selling price.
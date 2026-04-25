# Insurance Premium Prediction using Machine Learning

This project aims to predict **insurance premium charges** based on customer attributes such as age, BMI, smoking status, number of children, and region using machine learning models.The project compares multiple regression algorithms to identify the best-performing model for accurate prediction.


Dataset
 File: `insurance.xls`
 Features:
  * Age
  * Gender
  * BMI
  * Children
  * Smoker
  * Region
Target Variable:
  * Charges (Insurance Premium)



Technologies Used
* Python 
* Pandas
* NumPy
* Scikit-learn



Data Preprocessing
* Handled categorical variables using encoding
* Checked for missing values
* Feature selection
* Train-test split (80:20)


Models Implemented
1. Linear Regression
* Baseline model
* Assumes linear relationship

2. Ridge Regression
* Regularization technique (L2)
* Reduces overfitting

3. Random Forest Regressor
* Ensemble learning method
* Handles non-linear relationships effectively


Results
| Model             | R² Score |
| ----------------- | -------- |
| Linear Regression | 0.784    |
| Ridge Regression  | 0.783    |
| Random Forest     | 0.865    |


Key Insights
* Random Forest achieved the highest accuracy (~86.5%)
* Linear and Ridge Regression showed similar performance
* Smoking status significantly impacts insurance charges
* Non-linear models perform better for this dataset


Conclusion
Random Forest Regressor is the most suitable model for predicting insurance premiums due to its ability to capture complex patterns and interactions in the data.


Future Improvements
* Hyperparameter tuning (GridSearchCV)
* Try advanced models like XGBoost
* Feature engineering
* Deployment using Flask / Streamlit


Author
Aniruddha Somani


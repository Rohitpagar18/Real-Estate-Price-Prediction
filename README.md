# Real-Estate-Price-Prediction

The aim of this project is to predict real estate prices based on various factors using different machine learning models. The dataset used contains information on property transactions, including attributes such as house age, distance to the nearest MRT station, number of convenience stores nearby, latitude, and longitude. The target variable is the house price per unit area.
This project demonstrates the use of various regression techniques to predict real estate prices based on several influencing factors. By carefully cleaning the data, removing outliers, and selecting appropriate models, it provides an effective approach to understanding and predicting house prices. The models can be further fine-tuned, or more sophisticated techniques can be applied to improve predictions and gain deeper insights into the real estate market dynamics.
📌 Project Description: - The main objective is to build a regression model to predict a target variable based on the provided dataset:

✔️ Data Preprocessing: Conducted thorough data cleaning by handling missing values, detecting and removing duplicate records, and addressing outliers to ensure data quality and reliability.

✔️ Feature Engineering: Applied polynomial feature transformation to explore non-linear relationships and enhance model performance. Checked for multicollinearity and performed feature selection to retain significant predictors. Implemented normalization and standardization techniques to prepare data for model training.

✔️ Model Development: Developed and compared several regression models, including #Polynomial Regression and #XGBRegressor. Polynomial Regression was initially used to capture non-linear trends in the data. Then, an XGBRegressor model was implemented for enhanced predictive performance and robustness.

✔️ Model Evaluation and Optimization: Both models were evaluated using metrics such as RMSE, MSE, MAE, and R²-Score. The XGBRegressor outperformed Polynomial Regression in terms of R² and RMSE, indicating better accuracy and generalization capability. The models were further fine-tuned using hyperparameter tuning techniques to optimize performance and reduce overfitting.

✔️ Results: The XGBRegressor demonstrated superior performance with lower error rates and higher predictive power compared to Polynomial Regression, proving to be a more effective model for this task.


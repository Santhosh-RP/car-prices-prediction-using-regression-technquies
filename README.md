# car-prices-prediction-using-regression-technquies
![20231204054911_Honda 9](https://github.com/user-attachments/assets/499e554a-5379-4be4-90b9-2880cb555c3c)

Dataset Description
This dataset explores several features related to cars:

brand: The make or manufacturer of the car (e.g., Toyota, Ford, BMW).
model: The specific model of the car (e.g., Corolla, Mustang, 3 Series).
model_year: The year the car model was manufactured or released.
milage: The total distance the car has been driven, typically measured in miles or kilometers.
fuel_type: The type of fuel the car uses (e.g., petrol, diesel, electric, hybrid).
engine: Information about the car's engine, including details such as displacement (e.g., 2.0L, 3.5L) or engine configuration.
transmission: The type of transmission the car has (e.g., manual, automatic, CVT).
ext_col: The exterior color of the car (e.g., red, black, silver).
int_col: The interior color of the car (e.g., beige, black, gray).
accident: Indicates whether the car has been in an accident (likely a binary feature, e.g., yes/no).
clean_title: Indicates whether the car has a clean title, meaning it hasn't been severely damaged or written off (likely a binary feature, e.g., yes/no).
price: The selling price of the car, which is the target variable for regression analysis.
In this project, I performed the following steps:

Data preprocessing
Handling outliers
Feature engineering
Feature selection
Model selection
This dataset was used for a regression problem. I applied various regression algorithms and obtained the following results:

Linear Regression:

R²: 0.7120
MAE: 0.3157
MSE: 0.1749
RMSE: 0.4182
Ridge Regression:

R²: 0.7120
MAE: 0.3157
MSE: 0.1749
RMSE: 0.4182
Lasso Regression:

R²: 0.6921
MAE: 0.3240
MSE: 0.1870
RMSE: 0.4325
ElasticNet Regression:

R²: 0.7048
MAE: 0.3163
MSE: 0.1793
RMSE: 0.4235
Decision Tree Regression:

MAE: 0.2733
MSE: 0.1268
RMSE: 0.3562
This version clarifies the dataset's description, the steps performed in the project, and the results of various regression algorithms.

# Linear-Regression
Predict house prices using Multiple Linear Regression with Python. Includes data preprocessing, model training, evaluation (MAE, MSE, R²), and visualization
# Linear Regression – Housing Price Prediction

## Objective

Predict house prices using **Linear Regression** with features like area, bedrooms, bathrooms, etc.

## Dataset

* File: `housing.csv`
* Columns: `price` (target), `area`, `bedrooms`, `bathrooms`, `stories`, `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `parking`, `prefarea`, `furnishingstatus`

## Steps

1. Import libraries: Pandas, Matplotlib, Seaborn, Scikit-learn
2. Load dataset and check data info
3. Encode categorical columns using LabelEncoder
4. Visualize data with heatmap and pairplot
5. Split data into training (80%) and testing (20%) sets
6. Train Linear Regression model
7. Predict and evaluate using MAE, MSE, R²
8. Visualize Actual vs Predicted prices
9. Check feature coefficients to see which features impact price most

## Evaluation Metrics

* **MAE:** Mean Absolute Error
* **MSE:** Mean Squared Error
* **R²:** How well the model fits the data

## Tools Used

* Python, Pandas, Matplotlib, Seaborn, Scikit-learn

## Outcome

* Understand Linear Regression (simple & multiple)
* Learn data preprocessing and model evaluation
* Visualize predictions and interpret coefficients

**Author:** Prince Kumar

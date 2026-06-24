# Task 6: House Price Prediction

## Objective

The objective of this project is to predict house prices using various property features such as area, number of bedrooms, bathrooms, floors, year built, location, condition, and garage availability. A machine learning regression model is trained to estimate house prices based on these features.

---

## Dataset

**Dataset:** House Price Prediction Dataset (Kaggle)

The dataset contains information about residential properties, including:

* Id
* Area
* Bedrooms
* Bathrooms
* Floors
* YearBuilt
* Location
* Condition
* Garage
* Price (Target Variable)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## Project Workflow

### 1. Data Loading

The dataset was loaded using Pandas and inspected for structure, data types, and missing values.

### 2. Data Preprocessing

* Handled missing values.
* Encoded categorical features such as Location and Condition using Label Encoding.
* Separated features and target variable.
* Applied StandardScaler for feature scaling.

### 3. Train-Test Split

The dataset was divided into:

* Training Set: 80%
* Testing Set: 20%

### 4. Model Training

A Linear Regression model was trained using the training dataset.

### 5. Prediction

The trained model was used to predict house prices on the testing dataset.

### 6. Model Evaluation

The model performance was evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### 7. Visualization

A scatter plot was generated to compare Actual House Prices and Predicted House Prices.

---

## Evaluation Metrics

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted house prices.

### Root Mean Squared Error (RMSE)

Measures the square root of the average squared prediction errors.

### R² Score

Indicates how well the model explains the variation in house prices.

---

## Results

The trained regression model successfully predicted house prices based on property features.

Example output:

MAE: [Your MAE Value]

RMSE: [Your RMSE Value]

R² Score: [Your R² Value]

---

## Sample Prediction

Example property:

* Area: 2500 sq ft
* Bedrooms: 4
* Bathrooms: 3
* Floors: 2
* Year Built: 2018
* Location: Encoded Value
* Condition: Encoded Value
* Garage: Yes

The trained model predicts the estimated market price of the property.

---

## Skills Demonstrated

* Regression Modeling
* Data Preprocessing
* Feature Scaling
* Feature Encoding
* Data Visualization
* Model Evaluation
* House Price Prediction

---

## Folder Structure

Task6_House_Price_Prediction/

├── House_Price_Prediction.ipynb

├── house_price_dataset.csv

├── README.md

└── prediction_plot.png

---

## Conclusion

This project demonstrates the application of machine learning regression techniques for real estate price prediction. By utilizing property characteristics and preprocessing techniques, the model can estimate house prices and assist in data-driven decision-making within the real estate domain.

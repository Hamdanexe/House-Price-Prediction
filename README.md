## 1. House Price Prediction

### Objective
Predict house prices based on property features such as size, number of bedrooms/bathrooms, year built, and location.

### Dataset
- **File:** `house_prices.csv`
- **Features:**  
  - SquareFeet (numeric)  
  - Bedrooms (numeric)  
  - Bathrooms (numeric)  
  - Location (categorical: Downtown, Suburb, Countryside)  
  - YearBuilt (numeric)  
  - Price (target variable)

### Models Applied
- **Linear Regression** (scikit-learn) for regression analysis.
- Preprocessing:
  - One-hot encoding for categorical data.
  - Standardization of numerical features.

### Key Results & Findings
- The model achieved a reasonable fit between actual and predicted prices.
- **Location** and **SquareFeet** had the highest impact on house prices.
- Evaluation Metrics:
  - MAE: ~ (varies by run)
  - RMSE: ~ (varies by run)

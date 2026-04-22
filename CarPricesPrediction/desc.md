# Car Prices Prediction

## Overview
This projects is aims to predict car prices in belarus using car features.The goal is to build a machine learning model that can estimate car prices accurately.


## Dataset
- Source: [Belarus Car Data](https://github.com/SUKHMAN-SINGH-1612/Data-Science-Projects/blob/main/Belarus%20Car%20Price%20Prediction/cars.csv)
- Number of rows: 56,244
- Number of columns: 12

| Variable        | Description                                                |
|-----------------|------------------------------------------------------------|
| make            | Car manufacturer                                           |
| model           | Car model                                                  |
| price USD       | Price in USD (target variable)                             |
| year            | Year of production                                         |
| condition       | Condition at the time of sale                              |
| mileage         | Mileage in kilometers                                      |
| fuel type       | Type of fuel (electric, petrol, diesel)                    |
| volume(cm3)     | Engine volume in cubic centimeters                         |
| color           | Color of the car                                           |
| transmission    | Type of transmission                                       |
| drive unit      | Drive type (FWD, RWD, AWD)                                 |
| segment         | Car segment (e.g., SUV, sedan)                             |


## Tools & Tecnologies
- Python
- Pandas
- NumPy
- Seaborn
- Scikit-learn
- Decission Tree Regression


## Workflow
### 1. Data Cleaning
- Removed unnecessary columns
- Filtered data
- Handled missing values
- Created new feature by grouping car brands into categories

### 2. Exploratory Data Analysis
- Visualized categorical distributions
- Visualized numerical distributions
- Identified top car brands by average price
- Explored price trends based on:
  - Condition
  - Transmission
  - Fuel type
  - Brand category

### 3. Feature Engineering
- Use label encoding to encode categorical variables
- Analyzed feature correlations using heatmap

### 4. Modeling
- Split data into training and testing
- Using Decission Tree Regression model
- Tune hyperparameters using GridSearchCV

## Result
The Decision Tree model achieved strong performance with an R² score of 0.8684, a Mean Absolute Error (MAE) of 1331, and a Root Mean Squared Error (RMSE) of 2051. The analysis shows that car price is primarily influenced by factors such as production year and mileage, where newer cars tend to have higher prices while higher mileage reduces value. Overall, the model provides a baseline for car price prediction.
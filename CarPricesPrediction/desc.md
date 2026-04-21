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
- 
### 4. Modeling
- Using Decission Tree Regression model
- Split data into training and testing
- Evaluate model

## Result

## Conclusion
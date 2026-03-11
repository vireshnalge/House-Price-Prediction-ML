# House Price Prediction using Machine Learning

## Problem Statement
Predict house prices based on property features such as
area, number of bedrooms, location, and house grade.

## Dataset
The dataset contains ~21,000 housing records with features including:
- Bedrooms
- Bathrooms
- Flat Area
- Lot Area
- House Grade
- Latitude / Longitude

## Machine Learning Models Used
- Linear Regression
- Decision Tree
- Random Forest
- Tuned Random Forest
- XGBoost

## Best Model
XGBoost Regressor

Performance:
R² Score: 0.886
MAE: 65,590
RMSE: 128,539

## Key Insights
The most influential features for predicting house prices were:
- Flat Area
- Overall Grade
- Location
- Number of Bathrooms

## Project Structure
data/ → dataset  
notebooks/ → analysis and modeling  
models/ → trained model  
outputs/ → visualizations  
src/ → reusable scripts
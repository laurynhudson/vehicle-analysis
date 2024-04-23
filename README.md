# vehicle-analysis

Follow along with the anaylsis by opening up the jupyter notebook file titled prompt_11.ipynb in your jupyter environment.

## Summary

This report presents the findings from my analysis aimed at identifying key drivers that affect used car prices. 

Objective: To determine the factors that most significantly influence the prices of used cars.

Methods: Utilization of models including Linear Regression and Ridge to predict car prices based on vehicles dataset.

Data: Dataset containing details about cars such as make, model, year, mileage, condition, and other features.


Data Cleaning: Addressed missing values.

Feature Engineering: Used target encoding to encode categorical values.

Visualizations: Created plots to understand the distribution and relationship of individual features with car prices.


Model Selection: Evaluated two models, Linear Regression andRidge.

Performance Metrics: Used Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) to assess model performance.

Findings and Insights

Key Drivers: The models highlighted several key factors influencing car prices:
The model used for analytics (Ridge) suggests that each additional year (being newer cars) increases the car's value. 

It suggests that higher mileage significantly reduces the car's value.
Recommendations

Inventory Management: It is better to maintain an inventory with more new cars and fewer used cars. When looking to add used cars to your inventory, you should be mindful of adding used cars that have the lowest mileage.
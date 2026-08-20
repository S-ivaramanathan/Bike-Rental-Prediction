# Bike Rental Prediction

## Project Overview

This project focuses on predicting bike rental demand using machine learning regression techniques.

The objective is to analyze historical bike rental data, understand the factors affecting rental demand, and build machine learning models to predict the total number of bike rentals.

## Dataset

The project uses the Bike Sharing dataset.

The dataset contains information such as:

- Date and time-related features
- Season
- Year
- Month
- Holiday
- Weekday
- Working day
- Weather situation
- Temperature
- Feeling temperature
- Humidity
- Windspeed
- Bike rental count

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Import required libraries
2. Load the bike rental dataset
3. Understand the dataset
4. Perform exploratory data analysis
5. Analyze the relationship between features and bike rental demand
6. Prepare the features and target variable
7. Split the dataset into training and testing data
8. Train multiple machine learning regression models
9. Generate predictions
10. Evaluate and compare model performance

## Machine Learning Models

The following regression models were implemented and compared:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- AdaBoost Regressor

## Model Evaluation

The models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

### Model Performance

| Model | R² Score | MAE | RMSE |
|---|---:|---:|---:|
| Gradient Boosting | 0.890603 | 462.770118 | 662.321482 |
| Random Forest | 0.879901 | 435.841614 | 693.961279 |
| Linear Regression | 0.827667 | 617.393066 | 831.285155 |
| AdaBoost | 0.802670 | 671.551455 | 889.532814 |
| Decision Tree | 0.758542 | 662.802721 | 983.981334 |

## Best Performing Model

Based on the R² Score, **Gradient Boosting Regressor** achieved the best performance among the evaluated models with an R² Score of **0.890603**.

Random Forest achieved the lowest MAE among the compared models, with an MAE of **435.841614**.

## Conclusion

This project demonstrates how machine learning regression techniques can be applied to predict bike rental demand.

Multiple regression models were trained and evaluated using R² Score, MAE, and RMSE. Among the evaluated models, Gradient Boosting provided the highest R² Score and showed the strongest overall predictive performance based on this evaluation.

## Project Files

- `Bike_Rental.ipynb` – Complete Jupyter Notebook containing data analysis, model building, predictions, and evaluation.
- `day.csv` – Bike sharing dataset used for the analysis.
- `hour.csv` – Hourly bike rental dataset.

## Skills Demonstrated

- Data Cleaning and Preparation
- Exploratory Data Analysis
- Data Visualization
- Feature Analysis
- Regression
- Machine Learning Model Building
- Model Evaluation
- Python Programming

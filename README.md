# Airline Route Demand Prediction

## Project Overview

This project develops and evaluates machine learning models to predict monthly airline departures using historical airline scheduling data from the SABRE Market Intelligence Database.

The objective is to demonstrate how predictive analytics can support airline network planning, fleet allocation, and scheduling decisions while following responsible machine learning practices.

---

## Business Problem

Airlines must determine how many departures to schedule across thousands of routes while balancing demand, operating costs, and aircraft availability.

Accurate demand forecasting helps airlines:

- Improve network planning
- Optimize fleet utilization
- Support schedule development
- Improve operational efficiency

---

## Dataset

Source:

- SABRE Market Intelligence Database

Dataset Characteristics:

- 250,786 flight records
- 20 modeling variables
- Airline schedules throughout North America

Data preparation included:

- Removing missing values
- Removing redundant variables
- Encoding categorical features
- Training/testing split (80/20)

---

## Machine Learning Models

Two supervised learning models were developed:

- Linear Regression
- Random Forest Regression

Performance was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Coefficient of Determination (R²)

---

## Major Finding

During model development, an unexpected case of data leakage was discovered.

After removing the leakage variable and retraining the model, the Random Forest algorithm produced reliable and realistic predictive performance suitable for business decision support.

---

## Repository Contents

```
notebooks/
    Airline_Routes_Prediction_Code.ipynb

report/
    Airline_Route_Prediction_Report.pdf

presentation/
    Airline_Route_Prediction_Presentation.pdf
```

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- SQLite
- Jupyter Notebook

---

## Future Improvements

Potential enhancements include:

- Incorporating real-time flight schedule updates
- Adding weather and economic indicators
- Hyperparameter optimization
- Time-series forecasting models
- Interactive dashboards

---

## Author

Giselle Dos Santos

Master of Science in Data Science

Bellevue University

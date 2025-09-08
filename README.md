# House Price Prediction

This repository contains a Jupyter Notebook focused on exploring, cleaning, and modeling a housing dataset to predict house prices.

🔹 Dataset Overview

    Original dataset: California Housing Prices (CSV file)

    Includes demographic, geographic, and housing-related features

    After preprocessing:

        Train shape: (X_train, y_train)

        Test shape: (X_test, y_test)

🔹 Cleaning & Processing Steps

    Removed duplicates and handled missing values (total_bedrooms)

    Standardized column formats and data types

    Scaled numerical features with StandardScaler

    Split dataset into train (80%) and test (20%)

🔹 Feature Engineering

    New features created to improve predictive power:

    total_rooms_per_household – ratio of rooms per household

    population_per_household – household population density

🔹 Modeling & Evaluation

    Algorithm: Linear Regression

    Metrics:

        MSE (Mean Squared Error)

        RMSE (Root Mean Squared Error)

        R² Score

    Visualized Actual vs Predicted Prices

🔹 Tech Stack

    Python

    Pandas, NumPy

    Matplotlib, Seaborn

    Scikit-learn

    Jupyter Notebook

🔹 Purpose

    The processed dataset and trained model are optimized for:

    Exploratory Data Analysis (EDA)

    Housing trend visualization

    Predictive modeling of house prices

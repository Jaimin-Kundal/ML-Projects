# Taxi Fare Prediction using Linear Regression

## Overview
This project implements a **Linear Regression model using TensorFlow/Keras** to predict taxi fares in Chicago.  
It is inspired by the **Google Machine Learning Crash Course** and uses **31,000+ real-world taxi trip records**.

The workflow includes **separate Exploratory Data Analysis (EDA)**, feature scaling, model training, validation, and evaluation.

---

## Dataset
- **Source:** City of Chicago Taxi Trips Dataset  
- **Records:** ~31,000 trips (May 2022 subset)
- **Target:** `FARE`

### Features Used
- `TRIP_MILES` – Trip distance  
- `TRIP_SECONDS` – Trip duration  

---

## Methodology
- Performed **EDA** to analyze distributions and correlations
- Identified **trip distance and duration** as strongest predictors
- Applied **manual Z-score normalization**
- Trained a **Linear Regression model using Keras**
- Validated performance using **training vs validation loss curves**
- Evaluated using **Mean Squared Error (MSE)**
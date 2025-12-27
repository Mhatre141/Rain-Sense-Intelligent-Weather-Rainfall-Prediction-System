# Rain-Sense-Intelligent-Weather-Rainfall-Prediction-System
RainSense is a machine learning–based weather prediction system that forecasts whether it will rain tomorrow and estimates the expected rainfall amount (in mm) using historical weather data and real-time user input

Accurate short-term rainfall prediction is essential for daily planning in agriculture, travel, and outdoor activities. Traditional forecasts can be complex for users, so this project simplifies weather prediction into an easy-to-use, data-driven system.

-Solution

RainSense uses machine learning models to analyze weather patterns and provide:

A binary prediction: Will it rain tomorrow? (YES / NO)

A numerical prediction: Expected rainfall amount in millimeters

The system accepts only three simple user inputs, making it lightweight and user-friendly.

- Machine Learning Approach

Type: Supervised Learning

-Models Used:

Random Forest Classifier → Rain occurrence (YES / NO)

Random Forest Regressor → Rainfall amount (mm)

Why Random Forest?

Handles non-linear relationships

Robust to noise

Works well with real-world weather data

-Input Features

The model uses engineered average values:

Average Temperature (°C)

Average Humidity (%)

Average Wind Speed (km/h)

-System Workflow

Load and clean historical weather data

Perform feature engineering (average-based features)

Handle missing values using mean imputation

Train classification and regression models

Accept real-time user input

Predict rain occurrence and rainfall amount

-Tools & Technologies

Language: Python

Libraries: Pandas, NumPy, scikit-learn

ML Techniques: Classification, Regression, Feature Engineering

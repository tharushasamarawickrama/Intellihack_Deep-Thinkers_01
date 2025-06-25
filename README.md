# Intellihack_DeepThinkers_1Task

# 🌦️ Weather Forecasting using Machine Learning

This repository contains the solution to a machine learning competition task for predicting rain on a daily basis using historical weather data. The model helps smart agriculture systems optimize irrigation, planting, and harvesting plans based on hyper-local weather predictions.

## 📊 Problem Statement

You are a data scientist at a smart agriculture startup. Your task is to build a model that predicts whether it will rain or not, using the following features from the dataset:

- `avg_temperature`: Average temperature in °C  
- `humidity`: Humidity in percentage  
- `avg_wind_speed`: Average wind speed in km/h  
- `rain_or_not`: Binary label (1 = rain, 0 = no rain)  
- `date`: Date of observation

The goal is to predict the `rain_or_not` label and the probability of rain for the next 21 days.

---

## 🧩 Dataset

The dataset consists of daily weather records for 300 days with various inconsistencies such as:
- Missing values
- Formatting issues
- Incorrect entries

---

## 🧼 Part 1: Model Development (85%)

### ✅ 1. Data Preprocessing (20%)
- Handled missing values using imputation strategies
- Cleaned incorrect entries and formatted the date field

### 📊 2. Exploratory Data Analysis (30%)
- Correlation analysis between features and `rain_or_not`
- Distribution plots, boxplots, and time series trends

### 🤖 3. Model Training & Evaluation (20%)
Trained and compared the following models:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

### 🔧 4. Hyperparameter Tuning (10%)
- Grid Search with Cross-Validation
- Feature selection based on importance scores

### 🎯 5. Final Output (5%)
- The final model predicts both binary rain/no-rain outcome and **rain probability**

---

## ⚙️ Part 2: MLOps System Design (15%)

### 🔄 Real-time Prediction System Design

Designed a system that:
- Receives sensor data every minute
- Aggregates and predicts daily rain probability
- Handles IOT/sensor malfunctions and data irregularities

### 📈 System Diagram
Included in `Report-2.pdf`

### 🧱 Components
- **Data Ingestion Module**
- **Real-time Aggregator**
- **Anomaly Handler**
- **Model Inference Engine**
- **Result Dashboard/API**

---




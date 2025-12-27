# 🌍 Earthquake Prediction Model using Machine Learning

Earthquakes are natural disasters that occur unpredictably. While exact prediction of earthquakes (date, time, and location) is not scientifically guaranteed, historical seismic data can be analyzed using machine learning techniques to identify patterns and trends.

This project demonstrates how a **Neural Network model** can be built using historical earthquake data to predict **magnitude and depth** based on **time and location features**.

---

## 📌 Project Overview

- Uses historical earthquake data
- Converts date and time into Unix timestamps
- Visualizes earthquake occurrences on a world map
- Trains a neural network using Keras
- Optimizes hyperparameters using GridSearchCV
- Evaluates model performance on test data

---

---

## 📊 Dataset

The dataset contains global earthquake records with features such as:

- Date
- Time
- Latitude
- Longitude
- Depth
- Magnitude
- Source and metadata

**Selected features used for modeling:**
- Timestamp (converted from Date & Time)
- Latitude
- Longitude

**Target variables:**
- Magnitude
- Depth

---

## ⚙️ Libraries Used

```python
numpy
pandas
matplotlib
datetime
time
scikit-learn
keras
basemap


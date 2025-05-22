# ✈️ FlyPriceAI  
### Predicting Flight Fares Using Machine Learning

FlyPriceAI is a machine learning project that predicts flight ticket prices based on features like airline, travel route, duration, and more. Built using Python, this project demonstrates the end-to-end workflow of a data science project—from raw data wrangling to feature engineering to predictive modeling.

---

## 📌 Project Objective
To build a regression model that accurately predicts flight prices using a dataset containing various travel-related features.

---

## 📁 Dataset Overview
The dataset contains details for domestic flights in India, including:

| Feature         | Description                                     |
|----------------|-------------------------------------------------|
| Airline         | Name of the airline                             |
| Source          | City of departure                               |
| Destination     | City of arrival                                 |
| Route           | Flight path                                     |
| Duration        | Total travel time                               |
| Total Stops     | Number of layovers                              |
| Additional Info | Miscellaneous information                       |
| Price           | **Target variable** – ticket price in INR       |
| Journey Date    | Date of the journey                             |
| Departure Time  | Time of departure                               |
| Arrival Time    | Time of arrival                                 |

---

## 🛠 Tech Stack
- Python 3.x
- Pandas & NumPy
- Matplotlib & Seaborn (EDA)
- Scikit-learn (ML modeling)
- Jupyter Notebook

---

## 🔍 Key Concepts Applied
- 🧹 **Data Cleaning** – Handled missing values and inconsistent formats  
- 🛠 **Feature Engineering** – Extracted date/time components, encoded categorical variables  
- 📊 **EDA (Exploratory Data Analysis)** – Uncovered data patterns and relationships  
- 🤖 **Model Building** – Trained a `RandomForestRegressor`  
- 📈 **Model Evaluation** – RMSE, R² Score, and Cross Validation

---

## 📊 Model Performance
| Metric         | Value         |
|----------------|---------------|
| R² Score       | ~0.82         |
| RMSE           | ~1200 INR     |
| Best Model     | Random Forest |

---

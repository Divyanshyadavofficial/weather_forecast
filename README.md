# 🌧️ Rain Prediction Model

This project uses machine learning to predict whether it will rain **tomorrow** based on today's weather features like temperature, humidity, and pressure. It's a simple but effective binary classification model built with Python and scikit-learn.

---

## 📌 Problem Statement

Forecasting rain helps in planning agriculture, urban management, logistics, and more. This project predicts whether it will rain **the next day** using features such as:

- Maximum Temperature (`tmax`)
- Minimum Temperature (`tmin`)
- Humidity (`humidity`)
- Pressure (`pressure`)

---

## 📂 Dataset

The dataset contains **366 daily weather records** with the following columns:

| Column     | Description                         |
|------------|-------------------------------------|
| `date`     | Date of the observation             |
| `tmax`     | Maximum temperature of the day (°C) |
| `tmin`     | Minimum temperature of the day (°C) |
| `humidity` | Relative humidity (%)               |
| `pressure` | Atmospheric pressure (hPa)          |
| `rain`     | `1` if it rained the next day, else `0` |

---

## 🧠 Model

- **Model Used**:  Random Forest
- **Target Variable**: `rain` (binary classification)
- **Evaluation**:
  - Accuracy
  - Precision
  - Cross-validation

---

## 📊 Exploratory Data Analysis (EDA)

- Checked missing values and outliers
- Plotted temperature ranges vs rain likelihood
- Analyzed correlation between features

---

## 📈 Feature Engineering

- Added `temp_range = tmax - tmin`
- Normalized features using `StandardScaler`
- Used train-test split (80-20)

---

## 🛠️ Tech Stack

- Python
- scikit-learn
- pandas, NumPy, Matplotlib, seaborn
- joblib (for model serialization)

---



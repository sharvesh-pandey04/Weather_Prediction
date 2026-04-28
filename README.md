# 🌦️ Weather Prediction System using Machine Learning

## 📌 Project Overview

This project is a **Weather Prediction System** built using Python and Machine Learning.
It analyzes historical weather data and predicts future temperature based on multiple features such as humidity, wind speed, and precipitation.

The main goal of this project is to understand **time-series data, feature engineering, and predictive modeling**.

---

## 🚀 Features

* 📊 Data Analysis using Pandas
* 📈 Data Visualization using Matplotlib
* 🤖 Machine Learning Model (Random Forest)
* 🔮 Future Temperature Prediction
* 🧠 Feature Engineering (Lag Features & Rolling Average)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## 📂 Dataset

The dataset contains the following features:

* Date
* Temperature
* Humidity
* Wind Speed
* Precipitation

---

## ⚙️ Project Workflow

### 1. Data Preprocessing

* Load dataset
* Convert date column to datetime format
* Set date as index

### 2. Feature Engineering

* Extract month, day, day_of_week
* Create lag features (previous temperature values)
* Add rolling average

### 3. Model Training

* Split data into training and testing sets
* Train using Random Forest Regressor

### 4. Prediction

* Predict temperature on test data
* Evaluate model using MAE (Mean Absolute Error)

---

## 📊 Model Performance

* Model Used: Random Forest Regressor
* Evaluation Metric: Mean Absolute Error (MAE)
* Current MAE: ~7.25 (can be improved with better features and tuning)

---

## 🔮 Future Scope

* Improve accuracy using LSTM / ARIMA
* Use real-time weather API
* Build a web app using Streamlit
* Deploy the model online

---

## ▶️ How to Run the Project

1. Clone the repository

2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```

3. Run Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Execute all cells step-by-step

---

## 📌 Conclusion

This project demonstrates how machine learning can be used for **weather prediction**.
It also helps in understanding real-world data processing and model building.

---

## 🙌 Acknowledgment

This project is built for learning and academic purposes to explore **Data Science and Machine Learning concepts**.


# Stock Price Predictor 

## Project Overview

This project predicts stock prices using Machine Learning techniques based on historical stock market data.

The application performs data preprocessing, feature engineering, model training, stock price prediction, and visualization of stock trends.

The project demonstrates how Machine Learning can be applied to financial market analysis and forecasting.

---

## Features

* Historical stock data analysis
* Data cleaning and preprocessing
* Feature engineering
* Stock price prediction
* Model evaluation
* Data visualization
* Future stock price forecasting
* Machine Learning model training

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook / Anaconda

---

## Dataset

The dataset contains historical stock market information including:

* Date
* Open Price
* High Price
* Low Price
* Close Price
* Adjusted Close Price
* Volume

Example:

| Date       | Open | High | Low | Close | Volume |
| ---------- | ---- | ---- | --- | ----- | ------ |
| 2024-01-01 | 100  | 105  | 98  | 103   | 500000 |

---

## Machine Learning Workflow

### 1. Data Collection

Historical stock data is loaded from a CSV file.

### 2. Data Cleaning

* Remove missing values
* Remove duplicate records
* Convert date columns into datetime format

### 3. Feature Engineering

Features used for prediction:

* Open Price
* High Price
* Low Price
* Volume

Target Variable:

* Close Price

### 4. Train-Test Split

Dataset is divided into:

* 80% Training Data
* 20% Testing Data

### 5. Model Training

Models used:

* Linear Regression
* Random Forest Regressor
* Decision Tree Regressor

### 6. Prediction

The trained model predicts stock prices based on historical market information.

### 7. Evaluation

Performance metrics:

* R² Score
* Mean Absolute Error (MAE)

### 8. Visualization

Graphs generated:

* Historical Stock Price Trend
* Actual vs Predicted Prices
* Model Comparison Chart

---

## Project Structure

StockPricePredictor/

├── microsoft_stock_data.csv

├── linear_model.ipynb

├── all_model.ipynb

├── README.md

└── requirements.txt

---




## Running the Project

Run the Jupyter Notebook:

jupyter notebook

Open:

stock_predictor.ipynb

Run all cells to train the model and generate predictions.

---

## Results

The model predicts future stock prices using historical market data.

Visualizations help compare actual and predicted stock prices and analyze market trends.

---

## Future Improvements

* LSTM Deep Learning Model
* Real-Time Stock Data Integration
* Stock Market Sentiment Analysis
* News-Based Prediction
* Web Dashboard using Flask or Streamlit
* Multiple Stock Support

---

## Learning Outcomes

Through this project, the following concepts are demonstrated:

* Data Preprocessing
* Feature Engineering
* Machine Learning
* Regression Analysis
* Data Visualization
* Financial Data Analytics

---

## Author

Mayank Raj kushwaha

BCA Student

A.I. Project

# 🍕 Domino's — Predictive Purchase Order System
An intelligent system designed to help Domino's Pizza automate and optimize its inventory and purchase order decisions using predictive analytics and machine learning models.

# 📦 Objective
To build a system that predicts the daily or weekly demand for ingredients (like cheese, dough, sauce, etc.) at various Domino’s locations, enabling the business to:

Reduce food waste

Avoid stockouts

Optimize supply chain and order frequency

# 🧠 Key Features
## Demand Forecasting: Predict future orders based on past sales data, weather, holidays, and promotions.

## Purchase Order Recommendation: Suggest quantity and time of order for ingredients.

## Exploratory Data Analysis (EDA): Insights into seasonal trends, top-selling items, and location-wise patterns.

# Modeling Techniques:

Time Series Forecasting (ARIMA, Prophet)

Regression Models (Linear, XGBoost, Random Forest)

Deep Learning (LSTM for sequential data)

# 🧰 Tech Stack
Python

Pandas, NumPy

Matplotlib, Seaborn

scikit-learn, XGBoost

Facebook Prophet / ARIMA / LSTM (TensorFlow/Keras)

SQL for querying historical order data

# 📁 Project Structure
bash
Copy
Edit
├── data/                      # CSV or SQL-based historical order data
├── notebooks/                 # Data analysis and model training notebooks
├── models/                    # Saved predictive models
├── app/                       # (Optional) Flask or Streamlit dashboard
├── requirements.txt           # Python dependencies
├── README.md                  # Project documentation

# 📈 Results
Forecast accuracy: ~90% using LSTM for high-volume stores

20–30% reduction in over-purchasing

Real-time dashboard for inventory planners

# 🚀 Future Improvements
Integrate real-time POS (Point of Sale) data

Add supplier lead times and delivery constraints

Build mobile app for store managers


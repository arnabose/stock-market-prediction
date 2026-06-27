# Stock Market Prediction

A machine learning project that predicts Tesla stock closing prices using historical stock market data. The project compares multiple regression algorithms and evaluates their performance using standard machine learning metrics.

## Project Objective

The objective of this project is to analyze historical Tesla stock data and build regression models capable of predicting the stock's closing price based on market features such as opening price, highest price, lowest price, and trading volume.

---

## Dataset

The project uses historical Tesla stock market data containing:

* Date
* Open Price
* High Price
* Low Price
* Close Price
* Adjusted Close
* Volume

Dataset Location:

```text
dataset/tesla.csv
```

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Jupyter Notebook

---

## Machine Learning Models

The following regression algorithms were implemented and compared:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Support Vector Regressor (SVR)
* Support Vector Regressor with Standard Scaling

---

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Data Visualization
5. Feature Selection
6. Train-Test Split
7. Feature Scaling
8. Model Training
9. Model Evaluation
10. Stock Price Prediction
11. Model Comparison
12. Save Trained Model

---

## Model Evaluation

Models were evaluated using:

* R² Score
* Mean Squared Error (MSE)

The project compares multiple regression models to identify the best-performing algorithm for stock price prediction.

---

## Results

The notebook includes:

* Tesla Stock Price Trend
* Model Performance Comparison
* Actual vs Predicted Closing Price Graph

Screenshots will be added in the `screenshots` folder.

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/arnabose/stock-market-prediction.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run

Open:

```text
stock-price-prediction.ipynb
```

and execute the notebook.

---

## Project Structure

```text
Stock-Market-Prediction
│
├── stock-price-prediction.ipynb
├── dataset/
│   └── tesla.csv
├── screenshots/
├── requirements.txt
├── stock_price_ml_model.pkl
└── README.md
```

---

## Learning Outcomes

This project helped strengthen my understanding of:

* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Data Visualization
* Regression Algorithms
* Model Evaluation
* Machine Learning Workflow
* Predictive Analytics

---

## Future Improvements

* Deep Learning using LSTM
* Hyperparameter Tuning
* Predict Multiple Stocks
* Real-time Stock Price Prediction
* Interactive Dashboard using Streamlit

---

## Author

**Arnab Bose**

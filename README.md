# Gold Price Prediction using Machine Learning

This project focuses on predicting gold prices using historical data and machine learning techniques. It demonstrates a complete data science workflow, including data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and result visualization using Python.

The repository is intended for learning, experimentation, and demonstration of regression-based machine learning models applied to real-world financial data.

---

## Project Overview

Gold is a globally traded commodity whose price is influenced by multiple economic and market factors. By analyzing historical gold price data, this project builds predictive models that estimate future gold prices based on observed patterns in the data.

The project is implemented entirely in a Jupyter Notebook for clarity and step-by-step analysis.

---

## Features

- Loading and preprocessing historical gold price data
- Data cleaning and handling missing values
- Exploratory Data Analysis (EDA) using visualizations
- Feature selection and correlation analysis
- Training multiple regression models
- Performance evaluation using standard regression metrics
- Visualization of actual vs predicted prices

---

## Machine Learning Models Used

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

---

## Evaluation Metrics

Models are evaluated using the following metrics:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics help assess prediction accuracy and model reliability.

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost (optional)

---

## Repository Structure

```text

Gold-Price-Prediction/
├── Gold_Price_Prediction.ipynb # Main notebook containing analysis and models
├── gld_price_data.csv # Dataset used for training and evaluation
└── README.md # Project documentation

```

---

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or Jupyter Lab

### Installation

Install the required Python libraries:

```text
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```


---

## Usage

1. Clone the repository:
2. Navigate to the project directory.
3. Open `Gold_Price_Prediction.ipynb` in Jupyter Notebook.
4. Run the notebook cells sequentially to reproduce the results.

---

## Intended Use

- Educational purposes in machine learning and data science
- Practice project for regression modeling
- Demonstration of end-to-end ML workflow on financial data

---

## Limitations

- Uses historical data only; does not account for real-time market changes
- Predictions are based on available features and past trends
- Not intended for real-world trading or financial decision-making

---

## Future Enhancements

- Incorporate additional economic indicators
- Use time-series–specific models (ARIMA, LSTM)
- Add cross-validation and hyperparameter tuning
- Integrate real-time data sources

---

## Author

Maintained by Mohamed Asharaf.

# Car Price Prediction with Machine Learning

## Project Overview

This project showcases an end-to-end machine learning workflow to predict used car prices based on various features. The goal is to build a regression model that can accurately estimate the price of a car, providing valuable insights for both buyers and sellers in the used car market.

The analysis and model building are performed using Python, with a focus on core data science and machine learning libraries.

### Key Tasks & Methodology

1.  **Data Loading & Initial Exploration**: Load the dataset and perform an initial review of its structure, data types, and summary statistics.
2.  **Exploratory Data Analysis (EDA)**: Visualize key relationships between features (e.g., `mileage`, `year`, `brand`) and the target variable (`price`) to identify patterns and potential insights.
3.  **Data Preprocessing**: Handle missing values using imputation and prepare categorical features for model consumption using one-hot encoding.
4.  **Model Training**:
    * Split the data into training and testing sets.
    * Train two regression models:
        * **Linear Regression**: A baseline model to establish a simple benchmark.
        * **Random Forest Regressor**: A more robust ensemble model to capture non-linear relationships and improve predictive accuracy.
5.  **Model Evaluation**: Evaluate the performance of both models using metrics such as $R^2$ score to determine which model is more suitable for this problem.

### Dataset Description

The dataset used is a fictional CSV file named `cars.csv`, containing information on various car listings. It includes the following fields:

- `brand` : Brand of the car (e.g., Toyota, Ford).
- `model` : Model of the car (e.g., Camry, F-150).
- `year` : Manufacturing year of the car.
- `mileage` : The car's mileage.
- `color` : The color of the car.
- `engine_size` : The size of the car's engine.
- `price` : The target variable - the price of the car.

### Technologies and Libraries Used

* **Python**: The core programming language.
* **Jupyter Notebook**: For an interactive and reproducible analysis environment.
* **Pandas**: Essential for data loading, cleaning, and manipulation.
* **NumPy**: For numerical operations.
* **Matplotlib & Seaborn**: For data visualization.
* **Scikit-learn**: The primary library for machine learning, including data preprocessing (`SimpleImputer`, `OneHotEncoder`) and model training (`LinearRegression`, `RandomForestRegressor`).


### How to Run the Project

1. Clone this repository to your local machine.
2. Ensure you have Python installed. It is highly recommended to use a virtual environment.
3. Install the required libraries using the `requirements.txt` file:

   ```bash
   pip install -r requirements.txt

# XGBoost Regression Machine Learning Project - Big Mart 

## 1. Project Overview

This project implements an XGBoost Regressor for predicting calories burn. XGBoost is an optimized gradient boosting algorithm that excels in predictive power and speed, making it a popular choice for regression tasks.

## 2. Dataset Source

https://www.kaggle.com/datasets/fmendes/fmendesdat263xdemos

## 3. Features
- **Data Preprocessing**: Data cleaning, normalization, and splitting into training and testing sets.
- **Model Training**: Training XGBoost model using xgboost library.
- **Model Evaluation**: Evaluating the performance of the model using metrics such as R-square and Mean Absolute Error
- **Visualization**: Visualization of feature importance and model predictions versus actual values.


## 4. Project Structure
    ├── calories.csv                # Dataset file 
    ├── calories_burn.ipynb         # Jupyter notebook with end-to-end implementation
    ├── README.md                   # Project documentation
    ├── requirements.txt            # Python dependencies
    └── .gitignore                  # Files to be ignored in version control

## 5. Getting Started

### Prerequisites
- Python 3.9 or higher
- Jupyter Notebook
- scikit-learn
- xgboost
- pandas
- matplotlib
- numpy
- seaborn

### Installation
1. Clone the repository:

```python
    git clone https://github.com/adamsdossantos/calories.git
    
```
2. Create a virtual environment and activate it:
```python
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install the required packages:
```python
   pip install -r requirements.txt
```

4. Launch the Jupyter Notebook:
```python
    jupyter notebook calories_burn.ipynb
```
## 6. Usage

Open the calories_burn.ipynb file and follow the step-by-step instructions provided in the notebook. The notebook includes:

- **Data Loading and Preprocessing**: Load data from the BostonHousing.csv and perform necessary preprocessing and feature engineering.
- **Model Training**: Train an XGBoost Regressor with adjustable hyperparameters like learning_rate, n_estimators, max_depth, and more.
- **Model Evaluation**: Evaluate the model using metrics like RMSE, MAE and R² to measure regression accuracy.
- **Visualization**: Visualize feature importance using XGBoost's built-in plot functions and compare predicted versus actual values.

## 7. Results in Test

- **XGBoost Regressor**:
    | Metric    |  Value   |
    |-----------|----------|
    | Root Means Squared error  |  2.3   |
    | R-square |  0.99   |
    |Mean Absolute error | 1.4|


## 8. Contributing

Feel free to open issues or submit pull requests if you find any bugs or want to improve the project.

## 9. License

This project is licensed under the MIT License - see the LICENSE file for details.








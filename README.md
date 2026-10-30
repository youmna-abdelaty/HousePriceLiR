# House Price Prediction – Linear Regression

A simple linear regression pipeline built with Python and scikit-learn to predict house prices.

## Dataset

[House CSV – Kaggle](https://www.kaggle.com/datasets/mohamedbakrey/housecsv)

## Pipeline

1. **Data Loading** – download and read the CSV with Pandas
2. **Preprocessing** – remove duplicates, fill missing values, encode categorical columns, inspect distributions
3. **EDA** – correlation analysis and scatter plots of the top features against the target
4. **Modeling** – 80/20 train-test split and `LinearRegression` from scikit-learn
5. **Evaluation** – MSE, RMSE, MAE, R², and a regression line plotted against actual data points

## Requirements

- Python 
- pandas, numpy, matplotlib, scikit-learn, kagglehub

```bash
pip install pandas numpy matplotlib scikit-learn kagglehub
```

## Usage

1. Clone or download this repository.
2. Open `linear_regression_house.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
3. Run all cells from top to bottom.

## Project Structure

```
├── linear_regression_house.ipynb   # Main notebook
└── README.md
```

## Metrics

| Metric | Description |
|--------|-------------|
| MSE    | Mean Squared Error |
| RMSE   | Root Mean Squared Error |
| MAE    | Mean Absolute Error |
| R²     | Proportion of variance explained |

Results are printed in the Evaluation section of the notebook.

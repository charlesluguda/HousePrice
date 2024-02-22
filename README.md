# House Price Prediction Project

## Overview

The goal of this project is to predict house prices using the California Housing dataset. The XGBoost regression model is utilized for accurate predictions.

## Table of Contents

- [Dataset](#dataset)
- [Data Exploration](#data-exploration)
- [Model Building](#model-building)
- [Evaluation](#evaluation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The California Housing dataset, obtained from the sklearn.datasets library, serves as the foundation for this project. It encompasses various features related to block groups in California, with the target variable being the median house value.

## Data Exploration

Initial exploration includes:

- Displaying the first few rows of the dataset.
- Describing basic statistics.
- Checking for missing values.
- Visualizing the correlation matrix.

## Model Building

XGBoost, a popular gradient boosting algorithm, is employed for building the house price prediction model. The model is trained on a training set and evaluated on a test set.

## Evaluation

The model's performance is evaluated using metrics such as mean absolute error, mean squared error, and R-squared.

## Usage

To use this project:

1. Install the required dependencies (`pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `xgboost`).
2. Run the Jupyter Notebook or Python script.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- xgboost

Install the dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost

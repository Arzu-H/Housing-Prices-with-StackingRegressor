# Machine Learning Pipeline - README

## Overview
This repository contains a Jupyter Notebook (`main.ipynb`) that implements a machine learning pipeline for regression tasks. It includes data preprocessing, model selection, and hyperparameter tuning using `GridSearchCV`.

## Features
- Data preprocessing with `SimpleImputer`, `OneHotEncoder`, and `StandardScaler`
- Model training with `RandomForestRegressor`, `GradientBoostingRegressor`, `Ridge`, and `SVR`
- Hyperparameter tuning using `GridSearchCV`
- Performance evaluation using `mean_squared_error`, `mean_absolute_error`, and `r2_score`

## Requirements
To run the notebook, install the required dependencies using:
```bash
pip install pandas numpy scikit-learn matplotlib scipy
```

## Dataset
- The notebook expects two datasets: `train.csv` (for training) and `test.csv` (for evaluation).
- Ensure both files are in the working directory before executing the notebook.

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook main.ipynb
   ```
2. Run the cells sequentially to preprocess the data, train models, and evaluate performance.

## Results
The notebook evaluates different models and compares their performance using standard regression metrics. Results are displayed at the end of the notebook.

## License
This project is open-source. Feel free to modify and use it for educational or research purposes.


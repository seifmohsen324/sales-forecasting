# Walmart Weekly Sales Forecasting

This repository contains a Jupyter notebook that explores and compares regression models for predicting Walmart weekly sales. It uses the supplied train, test, store, and feature CSV files and includes time-derived features, model evaluation, visual comparisons, feature importance, and seasonal decomposition.

## Project files

```text
.
├── datasets/
│   ├── features.csv
│   ├── stores.csv
│   ├── test.csv
│   └── train.csv
├── sales_forcasting_walmart.ipynb
└── README.md
```

The notebook expects the CSVs in a `datasets` directory relative to the repository. If running notebook cells from a different working directory, update the data paths accordingly.

## Notebook workflow

1. Load the Walmart sales and store data.
2. Parse dates and join supporting store and economic-feature data.
3. Create date-based features and prepare training/evaluation data.
4. Fit and compare Linear Regression, Random Forest, XGBoost, and LightGBM regressors.
5. Review prediction metrics, feature importance, plots, and a seasonal decomposition.

This is a notebook-based experiment; it does not currently provide a packaged forecasting application or command-line entry point. The supplied test CSV is not described here as labeled evaluation data.

## Requirements

Python 3 and Jupyter Notebook or JupyterLab are required. The notebook imports:

- pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn
- XGBoost, LightGBM
- statsmodels

Install the notebook dependencies in your environment, then launch Jupyter from the repository root:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost lightgbm statsmodels jupyter
jupyter notebook
```

Open `sales_forcasting_walmart.ipynb` and run the cells in order.

## Notes

- Results depend on the supplied data and the train/test strategy implemented in the notebook.
- Forecasting metrics should be interpreted with attention to chronological ordering and potential time leakage.
- No performance scores are claimed here; reproduce them by running the notebook.

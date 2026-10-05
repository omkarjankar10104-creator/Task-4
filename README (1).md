# Assignment 3: Data Preprocessing

## Dataset

CarDekho used car listings (Car details v3)

Link: https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho

The file used is `cardekho.csv`. It has more than 8,000 rows, a mix of numeric and categorical columns, and missing values in mileage, engine, max_power and seats.

## Target

`high_price` is 1 when the selling price is 10 lakh (1,000,000) or more, and 0 otherwise. This gives an imbalanced target, with the high price cars as the smaller class.

## Files

- `assignment3_preprocessing.ipynb`: the notebook with all 12 questions
- `pipeline.joblib`: the fitted preprocessing pipeline (imputing, encoding, scaling)
- `README.md`: this file

## How to run

1. Open the notebook in Google Colab.
2. Upload `cardekho.csv` to Colab.
3. Run all cells from top to bottom.
4. The first cell installs `imbalanced-learn` for SMOTE.

# Saudi Used Cars Price Prediction

An end-to-end Machine Learning project that predicts used car prices in Saudi Arabia. Built as part of the NTI M05 program.

## What It Does

We trained and compared 4 regression models on a dataset of 8,248 used car listings scraped from Syarah.com. After cleaning, filtering outliers, and tuning hyperparameters, our best model was Gradient Boosting with an R² of 0.867.

## Results

| Model | Test R² | Test MAE (SAR) |
|---|---|---|
| Gradient Boosting | 0.867 | 12,893 |
| Random Forest | 0.799 | 15,908 |
| Decision Tree | 0.716 | 19,492 |
| Linear Regression | 0.454 | 31,541 |

## Files

- `data/raw/` — Original dataset (8,248 rows)
- `data/processed/` — Cleaned dataset (5,418 rows)
- `notebooks/` — The full project notebook (cleaning + modeling)

## How to Run

1. Clone this repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook in Jupyter or Google Colab

## Team

- Mohamed Ahmed Mohamed (Abdallah) — @mohamedahmed-DS
- Milad Ashraf Khalaf Mekhail

## Tech Stack

Python, pandas, numpy, matplotlib, seaborn, scikit-learn

# Titanic EDA

Exploratory Data Analysis on the Titanic dataset, structured as a
walkthrough of EDA fundamentals: column types, univariate analysis,
and bivariate analysis.

## Contents
- `EDA.ipynb` — full notebook. Covers:
  - **Why do EDA** — motivation and column-type taxonomy.
  - **Univariate analysis** on numerical columns (`Age`, `Fare`),
    including notes on distribution shape and dispersion.
  - **Univariate analysis** on categorical columns (`Survived`, etc.).
  - **Bivariate analysis** — relationships between columns.
- `train.csv` — Titanic training data (Kaggle).

## Run

```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook EDA.ipynb
```

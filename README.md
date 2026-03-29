# Fraud Detection EDA Project

## Overview
This project performs an Exploratory Data Analysis (EDA) on a synthetic fraud detection dataset (Credit Card Fraud Detection). The goal is to identify patterns, understand class imbalance, and prepared the data for predictive modeling.

## Dataset
The project uses the `fraudTrain.csv` and `fraudTest.csv` datasets. Due to their large size (>100MB), these files are excluded from the git repository and should be placed in the `Data/` directory locally.

## Key Findings
- **Fraud Rate:** 0.58% (Extremely imbalanced).
- **High-Risk Categories:** Grocery POS, Online Shopping, and Miscellaneous Online transactions.
- **Data Quality:** Clean dataset with no missing values.

## Contents
- `EDA.ipynb`: Jupyter Notebook containing the full analysis and visualizations.
- `plots/`: Generated visualization plots (excluded from git).

## Setup
1. Clone this repository.
2. Place `fraudTrain.csv` in the `Data/` directory.
3. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
4. Open the Jupyter Notebook to explore the findings.

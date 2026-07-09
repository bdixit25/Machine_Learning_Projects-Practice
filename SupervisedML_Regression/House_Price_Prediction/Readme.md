# California Housing Price Prediction

This project explores regression techniques to predict median house values in the California Housing dataset. The workflow includes data exploration, baseline linear regression, multi-variable regression, polynomial regression, and report generation.

## Project Overview

The main objective is to compare different regression models and identify which one provides the best predictive performance for housing prices.

### Models explored
- Simple linear regression
- Multi-variable linear regression
- Polynomial regression (second-degree and third-degree)

### Key findings
- The multi-variable linear regression model achieved the best overall performance.
- The project also includes visual analysis of feature distributions and correlations.

## Project Structure

- data/raw/housing.csv: original dataset
- data/processed/housing_filtered.csv: cleaned dataset used for modeling
- notebooks/: Jupyter notebooks for EDA and model evaluation
- figures/: saved plots and visualizations
- reports/: LaTeX report source and compiled PDF
- src/: place for reusable scripts (currently empty)

## Setup

1. Create and activate a Python environment.
2. Install the required dependencies:
   ```bash
   pip install -r Requirements.txt
   ```
3. Launch Jupyter Notebook or JupyterLab:
   ```bash
   jupyter lab
   ```

## Reproducing the Analysis

Open the notebooks in the following order:
1. notebooks/01_data_exploration.ipynb
2. notebooks/02_baseline_linear_regression.ipynb
3. notebooks/03_polynomial_regression.ipynb

The notebooks save figures to the figures/ directory.

## Building the Report

To build the PDF report:

```bash
cd reports
pdflatex -interaction=nonstopmode main.tex
```

Ensure that a LaTeX distribution such as TeX Live is installed.

## Dataset

The dataset used in this project is the California Housing Prices dataset, available from Kaggle.

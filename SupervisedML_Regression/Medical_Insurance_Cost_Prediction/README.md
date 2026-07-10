# Medical Insurance Cost Prediction

This project applies supervised regression techniques to predict medical insurance charges from demographic and health-related attributes. The workflow includes exploratory data analysis, feature preprocessing, model training, evaluation, and report generation.

## Project Goals
- Predict insurance charges using machine learning regression models.
- Compare several regression algorithms on the same dataset.
- Identify the most important predictors of insurance cost.
- Document the methodology and results in a professional report.

## Dataset
The project uses the Medical Insurance dataset, which contains 1,338 observations and variables such as:
- age
- sex
- BMI
- number of children
- smoking status
- region
- insurance charges

## Workflow
1. Load and inspect the dataset.
2. Perform exploratory data analysis and visualize variable distributions.
3. Encode categorical variables and prepare features for modelling.
4. Train and compare regression models such as Random Forest, Gradient Boosting, Elastic Net, and Stacking Regressor.
5. Evaluate models using MAE, RMSE, and $R^2$.
6. Generate plots and compile the report.

## Project Structure
- data/: contains the raw dataset
- notebooks/: contains the exploratory and modelling notebooks
- figures/: stores generated plots in PDF format
- reports/: contains the LaTeX report source

## Dependencies
The required libraries are listed in Requirements.txt.

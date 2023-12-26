## Overview

    This repository contains code for exploratory data analysis (EDA) and model development for the Playground Series - S3E25 Kaggle competition. The goal is to predict material hardness.

## Contents

    main.py: Main Python script containing the EDA and model building code.
    data/ (if applicable): Directory to store the training and test data (not included in this repo).
    images/ (if applicable): Directory to store generated plots (not included in this repo).
## Dependencies

    Python 3.x
    pandas
    NumPy
    scipy
    matplotlib
    seaborn
    plotly
    scikit-learn
    lightgbm
    kaggle
## Usage

    Install the required dependencies using pip install -r requirements.txt (if provided).
    Download the competition data from Kaggle using the provided command (kaggle competitions download -c playground-series-s3e25).
    Place the downloaded data in the data/ directory.
    Run the main.py script to execute the EDA and model building steps.
## Key Steps in the Code

    Data Loading:
     - Loads the training and test data from CSV files.
    Adversarial Validation:
    - Checks for potential leakage between training and test sets.
    Exploratory Data Analysis (EDA):
      - Examines data distributions, correlations, and feature interactions.
      - Identifies potential data quality issues and transformations.
    Feature Engineering:
     -  Applies Yeo-Johnson transformation to improve normality for some features.
    Modeling:
      - Trains and evaluates a decision tree model.
     -  Trains and evaluates a LightGBM model, including feature importance analysis.
## Additional Notes

The code includes code for generating various plots, but those plots are not included in this README.
The code is structured for clarity and reproducibility.
Consider using a virtual environment to manage dependencies.

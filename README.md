# Crossroads Classic Analytics Challenge 2025

This repository contains the code and analysis for the Crossroads Classic Analytics Challenge 2025, focusing on basketball analytics and prediction modeling.

## Project Overview

The project aims to analyze basketball data and develop predictive models for game outcomes. The analysis includes exploratory data analysis (EDA) and implementation of CatBoost models for predictions. Our model achieved an accuracy of 66% on the Kaggle competition leaderboard.

## Data Files

The project uses several key datasets (Data cannot be disclosed due to NDA):
- Training data with and without team names
- Test data with and without team names
- Division I Women's Basketball Contests data
- Institutions data

## Models

The project implements CatBoost models for prediction, including:
- Basic CatBoost implementation
- CatBoost with grid search for hyperparameter optimization

### Why CatBoost?

CatBoost was chosen as our primary model for several reasons:
1. **Handling Categorical Features**: CatBoost excels at handling categorical variables without requiring extensive preprocessing, which was crucial for our basketball dataset containing numerous categorical features like team names, venues, and game conditions.
2. **Robust Performance**: It provides strong performance with default parameters and is less prone to overfitting compared to other gradient boosting implementations.
3. **Efficient Training**: CatBoost's implementation is optimized for speed and memory efficiency, allowing us to iterate quickly on model improvements.
4. **Built-in Feature Importance**: The model provides clear insights into feature importance, helping us understand which factors most influence game outcomes.

## Getting Started

1. Clone this repository
2. Install required dependencies (Python packages)
3. Review the EDA notebook for data understanding
4. Run the CatBoost models for predictions

## Dependencies

- Python 3.x
- Jupyter Notebook
- CatBoost
- Pandas
- NumPy
- Other standard data science libraries

## License

This project is part of the Crossroads Classic Analytics Challenge 2025.

# Manhattan Rent Prediction

This project analyzes and predicts apartment rental prices in Manhattan using machine learning techniques. The dataset is sourced from StreetEasy and contains various features about rental listings, such as the number of bedrooms, bathrooms, square footage, amenities, and proximity to the subway.

## Project Workflow

1. **Data Loading & Exploration**
    - The dataset is loaded using pandas and basic exploration is performed to understand the structure and contents.

2. **Feature Selection & Correlation Analysis**
    - Correlation between features and the target variable (`rent`) is analyzed.
    - Highly correlated features are visualized using a heatmap, and multicollinearity is addressed by removing redundant features.

3. **Data Visualization**
    - Scatter plots and boxplots are used to visualize relationships between features and the target, and to detect outliers.

4. **Missing Value Analysis**
    - Null values are visualized and counted to ensure data quality.

5. **Model Selection & Cross-Validation**
    - Multiple regression models are evaluated using cross-validation:
      - Linear Regression
      - Ridge Regression
      - Lasso Regression
      - Random Forest Regressor
      - Support Vector Regressor (SVR)
    - The best-performing model is selected based on cross-validation scores.

6. **Model Training & Prediction**
    - The selected model is trained on the full dataset.
    - Predictions are made for new data samples.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## How to Run

1. Clone this repository.
2. Install the required dependencies.
3. Open the Jupyter Notebook and run the cells sequentially.
4. Modify the `new_data` variable to predict rent for custom apartment features.

## Example Prediction

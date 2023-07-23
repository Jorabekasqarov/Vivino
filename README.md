# Vivino
Wine Price Prediction
# Task
The task of this project is to predict wine prices based on various features such as ratings, wineries, years, reviews, regions, and countries. We aim to build regression models to predict the prices and evaluate their performance using the R-squared score.

# Description
This project uses a dataset called 'vivino_data.csv' containing information about different wines and their respective prices. The dataset is cleaned, and feature engineering is performed to extract meaningful information. Various data visualization techniques are used to explore the relationships between features and wine prices.

Three regression models - CatBoostRegressor, GradientBoostingRegressor, and LGBMRegressor - are implemented to predict wine prices. The models are trained on a portion of the dataset and evaluated using the R-squared score on the test data.

# Installation
To run this project, you need to install the required Python packages. You can do this using pip:

diff
Copy code
!pip install pandas seaborn matplotlib numpy scikit-learn lightgbm catboost
# Usage
Clone the repository and navigate to the project directory.
Ensure you have installed the required packages as mentioned in the installation section.
Run the Jupyter notebook or Python script containing the code.
The project will load the 'vivino_data.csv' dataset and perform data cleaning and visualization.
Regression models will be trained and evaluated to predict wine prices.
The R-squared scores of the models will be displayed, indicating their performance.
Note: Make sure to have the 'vivino_data.csv' dataset in the project directory before running the code.

This project demonstrates how to predict wine prices using machine learning techniques and provides valuable insights into the wine industry. It can be beneficial for wine enthusiasts, collectors, and sellers to make data-driven decisions.

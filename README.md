# Wine Quality Prediction

This project is focused on predicting the quality of red wines based on some chemical properties using different machine learning models from Ensemble family. The analysis was conducted using Python, and several models were explored to determine the most effective predictor.

## Key Features
**Data Exploration:** In-depth analysis of the dataset to understand relationships between features.
**Model Comparison:** Multiple models were trained and compared to identify the best performer.
**Hyperparameter Tuning:** Extensive tuning of model parameters to optimize performance.
**Visualization:** Various plots to visualize feature importance, correlations, and model performance.

## Technologies Used
Python: Main programming language used.
Pandas: For data manipulation and analysis.
Scikit-Learn: For model building and evaluation.
LightGBM & XGBoost: For advanced gradient boosting models.
Matplotlib & Seaborn: For data visualization.

## Project Overview

The project involves the following key steps:
1. **Data Preprocessing**: Handling missing values, encoding categorical variables, and standardizing the dataset.
2. **Exploratory Data Analysis (EDA)**: Visualizing relationships between features and the target variable (`quality`).
3. **Feature Selection**: Using correlation and model coefficients to select the most important features.
4. **Modeling**: Building and evaluating multiple models, including:
   - Linear Regression
   - Gradient Boosting Regressor
   - XGBoost Classifier
   - LightGBM Regressor
5. **Hyperparameter Tuning**: Optimizing model performance using `RandomizedSearchCV`.

## Dataset

The dataset used in this project is the [Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality) available from the UCI Machine Learning Repository. It contains various chemical properties of red wines and their corresponding quality scores (ranging from 3 to 8).

## Usage
1. Clone the Repository:
git clone https://github.com/mlais/quality_Wine.git
cd quality_Wine

4. Run the Jupyter Notebook:
Launch Jupyter Notebook and open the Exercicio_quality_Wine.ipynb file to explore the analysis and results.

5. Execute the Code:
You can run the cells in the notebook sequentially to reproduce the analysis, train models, and see the predictions.

## Acknowledgements
UCI Machine Learning Repository for providing the dataset.
The open-source community for the excellent libraries used in this project.

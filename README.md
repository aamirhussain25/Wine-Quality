# Wine-Quality
The project aims to predict the quality of wine based on various chemical properties using machine learning algorithms. This can help in quality control and optimizing the production process.

# Introduction
Wine quality is an important factor for both producers and consumers. This project leverages data science and machine learning to predict wine quality based on physicochemical tests. The dataset used contains various chemical properties of wine along with quality ratings.

# Data

The dataset used in this project is the [Wine Quality Data Set from the UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/186/wine+quality) ,It includes data for both red and white variants of the Portuguese "Vinho Verde" wine. The data includes the following features:

- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (target variable)

The data files included in this project are:

- winequality-red.csv: Data for red wine variants.
- winequality-white.csv: Data for white wine variants.
- winequality.names: Description of the dataset features.

# Quality Distribution
The histograms show the distribution of quality ratings for both red and white wines.

![Wine Quality Distribution](/Images/quality_distribution.png)

# Correlation of Features
The heatmap shows how different physicochemical properties correlate with each other and with the quality rating.

![Correlation of Wine Features](/Images/features_corr.png)

# Usage

The project is structured in a Jupyter notebook. You can run the notebook to see the data analysis, preprocessing steps, and model training. To start the notebook, use the command:

jupyter notebook wine_quality_project.ipynb

Modeling

The project explores several machine learning models to predict wine quality, including:

- Logistic Regression
- Random Forest
- MLPClassifier

Each model is evaluated using appropriate metrics, and hyperparameter tuning is performed to improve performance.

# Results

The performance of each model is evaluated based on accuracy, precision, recall, and F1 score. The results are compared to determine the best-performing model for predicting wine quality.

# Contributing

Contributions are welcome! If you have any suggestions or improvements, please create an issue or submit a pull request.





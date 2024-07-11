# MachineLearning_IncomePredictions_Pyspark
This project is a machine learning task using the adult dataset. The goal is to predict whether an individual's income is above or below 50K based on various features like age, education, occupation, etc.

The project involves the following steps:

## Data Collection: 
Loading the adult dataset from the UCI Machine Learning Repository. https://www.google.com/url?q=https%3A%2F%2Farchive.ics.uci.edu%2Fml%2Fdatasets%2Fadult
## Data Cleaning: 
Handling missing values and inconsistencies in the data.
## Feature Engineering: 
Transforming categorical features, normalizing numerical features, and preparing the data for modeling.
## Training: 
Building and training two models: Logistic Regression and Gradient Boosted Tree.
## Tuning and Evaluation
Performing hyperparameter tuning using cross-validation to optimize the models.
## Prediction
Making predictions on the testing set and evaluating model performance using areaUnderROC.

The project demonstrates a typical machine learning workflow, including data preprocessing, model training, and evaluation. It utilizes PySpark and SparkSQL for data manipulation and machine learning tasks.

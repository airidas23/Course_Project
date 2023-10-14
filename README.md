# P160B124_Machine_Learning_Methods
Machine Learning Methods, P160B124
# Project Title: Predictive Analysis of Bike Sharing Trends using Linear Regression

## Introduction
This project aims to apply linear regression to predict the hourly count of bike rentals over a span of one year. The dataset provided contains hourly rental data, with additional features such as the date, hour, temperature, and humidity, amongst others. The primary goal is to train a linear regression model on the training dataset to learn the associated coefficients and assess the model's accuracy using a separate testing dataset. The datasets are split such that the training dataset includes data from the first 25 days of each month, while the testing dataset includes the remaining days of each month.

## Dataset
The dataset is divided into two parts:
1. **Training Dataset:** For learning linear regression coefficients.
2. **Testing Dataset:** For assessing the accuracy of the trained model.

### Features
- Date
- Hour
- Temperature
- Humidity
- ... 

### Dependent Variable
- Rented Bike Count

## Tasks

### Task 1: Data Loading and Exploration
- Load the training and testing datasets (`train_bike.csv` and `test_bike.csv`).
- Explore the datasets to understand the number of features, types of these features, and the number of observations in both datasets.

### Task 2: Feature Visualization
- Select two features (excluding Date) and plot them against the Rented Bike Count.
- Discuss the potential usefulness of these features based on visual interpretation.

### Task 3: Correlation Analysis
- Compute the matrix of correlations between numerical variables using the `cor` function.
- Visualize the correlation matrix using the `ggcorrplot` library.
- Select a pair of features with the highest correlation and discuss the impact of removing one feature from the dataset.

### Task 4: Linear Regression Model Training
- Train a linear regression model using the `lm` function with Rented Bike Count as the response and all other variables (excluding Date) as predictors.
- Predict the count of rented bikes for the testing dataset and plot the predictions to evaluate the model.

### Task 5: Variable Transformation
- Apply a log transformation to the response variable to address any identified issues.
- Retrain the linear regression model and evaluate the model's performance using the R² measure of fit.

### Task 6: Interaction Effect Analysis
- Explore interaction effects between different features using the `*` symbol in the model formula.
- Evaluate the usefulness of interaction effects by comparing models with and without interaction terms.

### Task 7: Feature Transformation Exploration
- Explore different transformations (e.g., log, square root, square) for at least four numerical features.
- Evaluate the impact of these transformations on the model's performance.

## Data Files
- [Bike rent count test dataset](link_to_test_dataset)
- [Bike rent count train dataset](link_to_train_dataset)

## Instructions for Running the Code


## Results and Discussion


## References


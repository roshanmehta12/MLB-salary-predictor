# Major League Baseball Player Salary Predicton Project

This project aims to predict the salaries of baseball players based on various performance and demographic variables. We used the Hitters dataset in R and performed exploratory data analysis to understand the relationships between the variables. We then built several predictive models using linear regression, ridge regression, and principal component regression. We evaluated the performance of these models using mean squared error and compared their results to select the best performing model. The ultimate goal of this project was to provide insights to team managers and players regarding what factors are most important in determining player salaries.

## Introduction
This project aims to predict baseball player salaries using various performance and demographic variables. The Hitters dataset in R was used to perform exploratory data analysis and build predictive models.

## Data Preparation
The Hitters dataset contains information on Major League Baseball players' performance statistics and demographic variables from the 1986 season. We performed data cleaning to remove missing values and transformed categorical variables into numeric ones.

## Exploratory Data Analysis
We performed exploratory data analysis to understand the relationships between the variables. We created visualizations to identify any trends, patterns, or outliers in the data. We also calculated correlation coefficients between the variables to identify any significant correlations.

## Building Predictive Models
We built several predictive models using linear regression, ridge regression, and principal component regression. We used the `glm` package to build linear regression models and the `glmnet` package to build ridge regression models. We used the `pls` package to build principal component regression models.

## Model Evaluation
We evaluated the performance of the predictive models using mean squared error. We compared the results of each model to select the best performing one.

## Conclusion
In conclusion, this project aimed to predict baseball player salaries using various performance and demographic variables. We performed exploratory data analysis and built predictive models using linear regression, ridge regression, and principal component regression. The best performing model was used to identify the key factors that determine player salaries, providing valuable insights to team managers and players.

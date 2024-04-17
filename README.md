# Overview
This project aims to predict the points scored by NBA teams using polynomial regression. By analyzing various attributes such as team name, average number of weightlifting sessions, average number of yoga sessions, average number of laps run per practice, water intake, and number of players absent for sessions, we seek to uncover patterns and trends that contribute to a team's scoring performance.

# Objectives
- Predict points scored by NBA teams based on team attributes.
- Identify key factors influencing team scoring performance.
- Provide insights to coaches, team managers, and owners for informed decision-making.

# Dataset
The dataset used in this project contains the following attributes:

- Team name
- Points scored
- Average number of weightlifting sessions
- Average number of yoga sessions
- Average number of laps run per practice
- Water intake
- Number of players absent for sessions

# Methodology
## Exploratory Data Analysis (EDA)
- Cleaning and Transforming Data: Explain the steps taken to clean and transform the dataset. This may include handling missing data, dealing with outliers, encoding categorical variables, and scaling numerical features.
- Visualizing Data: Discuss the visualizations used to explore the dataset, such as histograms, scatter plots, box plots, and correlation matrices. Mention any insights gained from these visualizations.

## Imputation Techniques for Missing Data
- Provide an overview of different imputation techniques used to handle missing data, such as mean imputation, median imputation, mode imputation, K-nearest neighbors imputation, and using advanced models like Random Forest or LightGBM for imputation.

## Polynomial Regression
- Theory and Concepts: Explain the fundamentals of polynomial regression, including the difference between linear and polynomial regression, and how polynomial regression models capture nonlinear relationships between independent and dependent variables.
- Model Evaluation: Discuss methods used to evaluate the goodness of fit of polynomial regression models, such as R-squared, Mean Squared Error (MSE), and other performance metrics.
- Model Diagnostics: Describe techniques like ANOVA tables, residual plots, and model diagnostics to identify and address model assumptions and limitations.

## Chatterjee Correlation
- Concept: Explain what Chatterjee Correlation is and how it's used to evaluate the relationship between independent and dependent variables in a polynomial regression model.

## Model Selection
- AIC and BIC: Provide an overview of AIC (Akaike Information Criterion) and BIC (Bayesian Information Criterion), likelihood, and log likelihood. Explain how these metrics are used to compare and select the best-fitting polynomial regression model.

Results
The trained polynomial regression model achieved an accuracy of X%. Key factors influencing team scoring performance include weightlifting sessions, yoga sessions, laps run per practice, and player attendance.

Conclusion
Accurately predicting the points scored by NBA teams can provide valuable insights for coaches, team managers, and owners. By understanding the factors that contribute to scoring performance, teams can make informed decisions to improve their overall performance and success in the league.

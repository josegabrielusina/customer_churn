# Final Project

**Author**: Jose Gabriel Usina Mogro  
**Date**: 2023-11-27

## Overview

This project aims to predict whether a customer will leave the bank based on various attributes. The analysis involves data cleaning, visualization, and applying machine learning models, including a Random Forest and a Logistic Regression model.

## Data

The dataset used in this project is `Churn_Modelling.csv`, which includes the following key variables:

- `Exited`: The target variable indicating whether a customer has left the bank.
- `Geography`, `Gender`, `Age`, `Balance`, `NumOfProducts`, `IsActiveMember`, `HasCrCard`: Predictor variables used in the models.

## Steps

1. **Data Cleaning**: Unnecessary columns such as `RowNumber`, `CustomerId`, and `Surname` were removed. Key variables were converted to appropriate data types.

2. **Data Visualization**: Several visualizations were created to understand the distribution and relationships of the data, including:
   - Proportion of active members who exited.
   - Distribution of account balances by exit status.
   - Distribution of age by gender and geography.

3. **Model Building**:
   - **Random Forest**: A baseline Random Forest model was created and tuned to find the optimal number of variables (`mtry`) for the model.
   - **Logistic Regression**: A logistic regression model was used to provide interpretability on the impact of different variables on customer exit probability. Model selection was based on AIC and BIC criteria.

## Key Findings

- The Random Forest model provided a robust classification mechanism, and variable importance was analyzed to determine the most significant predictors.
- The Logistic Regression model gave insights into the odds of customer exit based on individual predictors, allowing for more straightforward interpretability compared to the Random Forest.

## Visualizations

Key visualizations included in the project are:
- Bar plots showing the relationship between active membership and customer exit.
- Histograms of account balances.
- Box plots of age by gender and geography.

## Conclusion

The project successfully demonstrates the process of data cleaning, visualization, and model building to predict customer churn. The Random Forest model offered high predictive performance, while the Logistic Regression model provided interpretative insights into the predictors of customer exit.

## Files

- `Final_Project.Rmd`: The main RMarkdown file containing the code and analysis.
- `Churn_Modelling.csv`: The dataset used for the analysis.

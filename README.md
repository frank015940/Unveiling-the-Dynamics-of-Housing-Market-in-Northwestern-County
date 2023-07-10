# Unveiling-the-Dynamics-of-Housing-Market-in-Northwestern-County

## Overview
* Business Understanding
* Data understanding
* Modeling
* Regression results
* Conclusion

## Business Understanding
Seldovatt Realtors wants to understand the factors that influence house prices in the county and develop a model that can accurately predict house prices based on those factors.

## Data Understanding
This project uses the King County House Sales dataset, which can be found in kc_house_data.csv. The description of the column names can be found in column_names.md. We've used the following features to analyze the dataset:

* id
* price
* bedrooms
* bathrooms
* sqft_living
* sqft_lot
* floors
* waterfront
* grade
* yr_built
* condition


## Modeling
I used multiple linear regression to model the house sales dataset. The preprocessing involved handling missing values and creating dummy variables. Relevant predictors such as  square footage, condition, and floors were selected. The model's performance was evaluated using metrics like MSE, RMSE, and R2. The coefficients were analyzed to understand the relationships between predictors and house prices. Regression diagnostics ensured the model's reliability and adherence to assumptions.

## Regression results
* The R_squared value indicated the model's goodness of fit
* The F_statistic is statistically significant since it's less than 0.05
* The regression coefficients provide insights into the magnitude and direction of the relationship between the predictor variable and house prices
* The Adjusted R-squared accounts for the number of predictors in the model, yielding a value of 0.585

## Conclusion
Utilize the regression model to guide pricing strategies, considering factors like square footage, bedrooms, and grade.
Focus on renovations that have a significant impact on house prices, such as increasing square footage or improving the condition of the house.

## Non Technical Presentation
To access the canvas slides click on the link [Presentation](https://www.canva.com/design/DAFj_a9dAPU/G8PCcq5VwJrDyH1PhXy5Cg/edit?utm_content=DAFj_a9dAPU&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
# Walmart Sales Forecasting Project

This project focuses on analyzing historical sales data from multiple Walmart stores to build predictive models for demand forecasting and uncovering key insights that drive sales. The project includes statistical analysis, model development, and evaluation, providing a data-driven approach to understanding sales patterns and influencing factors.

## Project Overview

**Objective:** Forecast weekly sales for Walmart stores using various regression models and determine the impact of external factors like CPI, unemployment rates, and fuel prices on sales.

**Data:** The dataset includes sales data from 45 Walmart stores across the United States, along with additional features such as holiday flags and economic indicators.

## Key Achievements

- **Model Development:** Built and evaluated five regression models (Linear, Ridge, Lasso, Random Forest, and Support Vector Regression) to predict weekly sales. The Random Forest model provided the best accuracy with an R² score of 0.3885.
- **Impact Analysis:** Identified significant correlations between sales and external factors, supporting the hypothesis that variables like CPI, unemployment, and fuel prices influence sales.
- **Statistical Insights:** Analyzed sales data to determine the store with maximum sales, evaluate sales volatility, and identify seasonal growth trends and holiday impacts.

## Methodology

**Data Preprocessing:**
- Converted dates into days starting from February 5th, 2010.
- Handled missing values and outliers to ensure data quality.

**Modeling:**
- Applied multiple regression techniques to forecast demand.
- Selected the Random Forest Regression model based on superior performance metrics (MAE, MSE, R²).

**Evaluation:**
- Assessed model accuracy using MAE, MSE, and R² metrics.
- Conducted comparative analysis to select the best-fit model for forecasting.

## Conclusion

The project successfully demonstrated the use of regression models for demand forecasting in retail, with actionable insights that can be leveraged to optimize sales strategies and inventory management.

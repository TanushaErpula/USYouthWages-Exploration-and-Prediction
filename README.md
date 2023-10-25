

# National Longitudinal Survey of Youth 1997 (NLSY97) Analysis

## Introduction
This project is focused on analyzing the National Longitudinal Survey of Youth 1997 (NLSY97). The dataset consists of interviews from 8,984 men and women born between 1980 and 1984 who resided in the United States in 1997. This cohort has been surveyed 18 times until the year 2020.

## Dataset Description
- **Original Dataset**: 1,52711 rows and 32 fields
- **Cleaned Dataset**: 1,41,392 rows and 18 areas
- **Features**: Year of birth (numeric), country of birth (text), sample race (text), area (text), number of children (numeric), family size (numeric), etc.

## Objective
Evaluate youth interviews done in 1979 in the United States.

## Methods Used
- **Linear Regression**: To create prediction models and explore relationships between variables.
- **Correlation Model**: To identify linear relationships between variables.
- **Stepwise Selection Method**: For the variable selection based on their significance level.

## Research Questions
1. Which ‘Race’ is getting the highest wages among all the other races?
2. Which Gender is getting paid the highest irrespective of their profession?
3. Which group in “marital status” gets the highest wages irrespective of the degree?
4. Define the correlation between gender and the wages they earn in their lifetime?

## Exploratory Data Analysis
- Summary Statistics Tables (not displayed here for brevity)
- Various bar charts to represent relationships between variables such as Race & Wage, Sex & Wage, Marital Status and Wage.
- Comparison charts to visualize data across different dimensions, e.g., Gender and Year.
- Correlation matrices to understand the linear relationships among variables.

## Prediction Models
- Several linear regression models focusing on:
  1. Wages based on the year (split into two periods: 1997-2004 and 2005-2013)
  2. Wages based on marital status

## Conclusion
In this project, we explored the dataset, performed data analysis, and developed regression models to answer the research questions. Our goal is to refine the model to achieve at least 90% accuracy in future iterations.

## References
1. [How to Interpret P-values and Coefficients in Regression Analysis by Jim Frost](https://statisticsbyjim.com/regression/interpret-coefficients-p-values-regression/)
2. [Multiple Linear Regression (MLR) Definition by Adam Hayes](https://www.investopedia.com/terms/m/mlr.asp)
3. [An introduction to multiple linear regression by Rebecca Bevans](https://www.scribbr.com/statistics/multiple-linear-regression/)
4. [Linear Regression Calculator](https://www.socscistatistics.com/tests/regression/default.aspx)
5. [Linear Regression - A Complete Introduction in R with Examples by Prabhakaran](https://www.machinelearningplus.com/machine-learning/complete-introduction-linear-regression-r/)

---

**Note**: This is a brief overview of the project. For detailed analysis, visualizations, and findings, please refer to the main project files in this repository.

# Simple Linear Regression

## INTRODUCTION
Simple Linear Regression is one of the basic statistic model we learn.
And frankly, R already made it easy to use.
But for you who are wondering how the formula could come up, this article will show you the step by step, without getting too much detail in statistic itself.

## TECHNICAL
Language: R (filetype: .rmd)

Library:
* tidyverse

## STEP BY STEP LINEAR REGRESSION
1. Start with the dataset, contains x - the predictor, and y - the target
2. PART 1: Find the Regression Formula
    * Count the Regression Formula y = a + bx, by determining the value of a and b.
    * Make the Prediction using formula #2.
    * Check the R-Squared
    * Plot the Linear Regression result
3. PART 2: Find the Residual
    * Count the Residual value
    * Plot the Residual result
4. PART 3: Find the Standardized Residual
    * Count the RSE
    * Count the Leverage
    * Count the Standardized Residual
    * Prepare the data for QQPlot
    * Create QQPlot of Standardized Residual

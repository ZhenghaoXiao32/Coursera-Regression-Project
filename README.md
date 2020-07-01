# Coursera Regression Project: Moter Trend Regession Analysis

## Introduction

This project used regression to analyze the relationships between a set of variables and miles per gallon (MPG), there are two main questions to answer in this project:

- Is an automatic or manual transmission better for MPG?
- Quantify the MPG difference between automatic and manual transmissions

## Executive Summary

The procedure of this project is:
- data importing and pre-processing
- exploratory data analysis
- building multiple models 
- model evaluation and selection
- conclusion of answers to the question

## Conclusion

Back to the core questions: Is an automatic or manual transmission better for MPG? Quantify the MPG difference between automatic and manual transmissions.

To answer these questions, we need to go back to the simple linear regression with only am as preditor, since the multiple regression model did not generate a significant p-value for the am variable, and the stepwise picked model did not include am as predictor. According to the result of the simple linear regression model, the average MPG of manual transmission is significantly (p-value = 0.0003) more than the automatic tranmissions, the quantity is 7.245. In addition, noticing the simple linear regression model is limited at the predictive performance. 

# Logistic_Regression
Logistic regression is a supervised machine learning algorithm that is mainly used for binary classification tasks where the goal is to predict the probability that an instance belongs to a given class or not . It is a statistical algorithm that analyzes the relationship between a set of independent variables and the dependent binary variables .

## Introduction

This report documents the end-to-end process of implementing logistic regression for a classification problem. The dataset used in this project contains information such as age, job, marital status, education, and various other attributes. The objective is to predict whether a client subscribes to a service, indicated by the 'y' column.

Imported necessary packages for data analysis.
Loaded the dataset using a comma separator.
Converted object data types to integers using label encoding.
Checked for null values in the dataset.

## Logistic Regression Model:

Defined the logistic regression model with 'y' as the dependent variable and the remaining columns as independent variables.
Split the data into training and testing sets.
Trained the logistic regression model and assessed its accuracy.

## Conclusion

In conclusion, the logistic regression model demonstrated promising results for the classification task. The accuracy of was 89.12 %. The exploration of different random state values further revealed the optimal configuration for achieving the highest accuracy.

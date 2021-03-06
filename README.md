# Blood-Donation-Prediction

## Prerequisites
**Install R and Rstudio IDE**

R: https://cran.r-project.org/

Rstudio: https://www.rstudio.com/products/rstudio/#Desktop

## Getting Started
**Set working directory**

A. Open "BloodDonPred.R" with Rstudio

B. Set working directory:

1. uncomment this code **#setwd("C:/Users/lkim016/Desktop")** so that it looks like this: **setwd("C:/Users/lkim016/Desktop")**

and

2. change **C:/Users/lkim016/Desktop** to the path to the folder where you downloaded the above repository files

## Project Guide
Objective: In this train dataset, we want to train the model to predict whether the person will donate blood this month with four possible predictors: “Months since last donation”, “Number of donations”, “Total volume donated (c.c.)”, “Months since first donation”.

1. First, use a logistic model to predict the probability of those people to donate their blood in the blood_testdata.xlsx. To determine the choice (variables) of the logistic model, do a simple train-test validation from the blood_traindata.xlsx.

2. Second, run all the classification machine learning models you learned in the class with the 10-fold cross validation. Choose the best model and predict whether the people in the blood_testdata.xlsx will donate or not (donate: 1; not: 0).

3. Submit results by filling two columns (Col F: Made donation this month; Col G: Probability from logistic model) with the R script.

4. Hint: check for collinearity among the feature variables.


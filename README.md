
# Introduction
This analysis attempts to predicate the probability for survival of the Titanic passengers. In order to do this, I will use the different features available about the passengers, use a subset of the data to train an algorithm and then run the algorithm on the rest of the data set to get a prediction.

In this analysis we have asked the following questions:
1)What is the relationship the features and a passenger’s chance of survival.
2)Prediction of survival for the entire ship.

# Titanic Survival Prediction
This repository contains some of my approaches to the Titanic survival prediction Problem from Kaggle.  The repository includes scripts for feature selection, alternate strategies for data modelling, the original test &amp; train data sets and the visualizations plots generated for the same. All code snippets are written in R.

In this popular challenge, the aim is to predict what sorts of people were likely to survive the Titanic disaster based on attributes such as gender, class, ticket details , age category e.t.c . 

## Code Example

TODO

## Motivation

One approach among the listed samples code was submitted to Kaggle.

## Installation

The datasets can be found in 'data' folder. It includes 2 csv files for train & test respectively.

train.csv (59.76 kb)  
test.csv (27.96 kb)

Following R packages are used.

seqinr: Biological Sequences Retrieval and Analysis
https://cran.r-project.org/web/packages/seqinr/index.html

e1071: Misc Functions of the Department of Statistics, Probability Theory Group (Formerly: E1071), TU Wien
https://cran.r-project.org/web/packages/e1071/index.html


party: A Laboratory for Recursive Partytioning
https://cran.r-project.org/web/packages/party/index.html


Amelia: Amelia II: A Program for Missing Data
https://cran.r-project.org/web/packages/Amelia/index.html

ggplot2: An Implementation of the Grammar of Graphics
https://cran.r-project.org/web/packages/ggplot2/index.html


https://cran.r-project.org/web/packages/corrgram/index.html
corrgram: Plot a Correlogram


## API Reference

Following scripts need to be run seprately

exploratory_data_analysis.R  -- All exploratory data analysis approaches analyzing data sets to summarize their main characteristics, building plots, creating map of missing features e.t.c

logistic_regression_solution.R -- Feature clean up, split of data set into train test, cross validation & survival prediction using Logistic Regression

random_forest_solution.R -- Feature clean up, split of data set into train test, cross validation & survival prediction using Random Forest

support_vector_machine_solution.R -- Feature clean up, split of data set into train test, cross validation & survival prediction using Support Vector Machine

final_baggged_solution.R -- Feature clean up, split of data set into train test, cross validation & survival prediction using all the above methods and then bagging the results.


## Plots

Some of the data visualizations are saved as pdfs in plots folder. Code for the same can be found in exploratory_data_analysis.R. The remaining visualizations like missmaps are printed in console itself.

Age_Distribution.pdf

Age_Vs_Survival.pdf

Embarked_Vs_Survival.pdf

Fare_Distribution.pdf

PClass_Distribution_Bar.pdf

survival_vs_sex.pdf

survived_vs_died.pdf

## Conclusion
The mean of the right predictions that I got on the test set is 0.76555 with the decision tree method, 0.77990 with the logistic regression model, and 0.80382 with the random forest model.

## Contributors
1)Soumwadeep Guha
2)Sagnik Saha
3)Surabhi Saha
4)Sanajit Bhunia
5)Nabin Das
6)Sajal Santra 

## License
None

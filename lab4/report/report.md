# MSE - MLDB - Lab 4 - TREFLE
## Authors:
- Romain Claret
- Edward Ransome

## Introduction
In this lab, we will use three datasets (Cancer, BCWD, GOLUB) and apply various fuzzy logic models to them using the Trefl library.

## Dataset cancer
### Question 1
The train/test seperation is done using a 66/33 split for all datasets.

We can see that there are more data points of class 0 than of class 1 (twice as many) but they are well distributed in the train/test split (the training set is always twice as large as the test set for both classes).
![](question1part0.png)

### Question 2
The number of rules indicates how many rules will be generated in the model. This will affect calculation time, but will increase accuracy on the training set.  To choose the optimal number of rules, one must refer to literature. However one can choose too many rules and overfit on the training data since some rules will represent noise in the data.

Variables per rule indicated how many variables can be used when defining a rule, for example the rule "IF v11 is low AND v4 is low THEN [0]" contains two variables. This means a rule can be more or less complex based on the number of variables: if many features interact to give a certain class, i.e. the problem is complex, more variables must be used per rule.

### Question 3
If we assume each rule uses different features, we can have at maximum 5*6 = 30 features used. However, the same variable can appear in multiple rules in practice.

### Question 4
TODO

### Question 6
### Question 7
### Question 8

## Dataset BCWD
### Question 1
### Question 4
### Question 6
### Question 7
### Question 8
### Question 9
### Question 10

## Dataset GOLUB
### Question 1
### Question 4
### Question 5
### Question 6
### Question 7
### Question 8
### Question 9
### Question 10
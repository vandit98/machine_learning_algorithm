
## Why decision tree?
1) Decision tress often mimic the human level thinking so its so simple to understand the data and make some good interpretations.

2) Decision trees actually make you see the logic for the data to interpret(not like black box algorithms like SVM,NN,etc..)


## What is decision tree?

A decision tree is a tree where each node represents a feature(attribute), each link(branch) represents a decision(rule) and each leaf represents an outcome(categorical or continues value).


## How many type of decision trees are there?
There are couple of algorithms there to build a decision tree , we only talk about a few which are

1) CART (Classification and Regression Trees) → uses Gini Index(Classification) as metric.

2) ID3 (Iterative Dichotomiser 3) → uses Entropy function and Information gain as metrics.



## so which one do we need to pick root node first?
Determine the attribute that best classifies the training data; use this attribute at the root of the tree.  use the attribute with the __highest information gain__ in ID3

## What is entropy and what is its significance?



## what is information gain and its significance?

It is the difference between parent entropy and average weighted entropy we found above.



## What are the disadvantage of decision tree?

__Overfitting__

Decision trees are prone to overfitting, especially when they are deep and complex. They can learn the training data too well, capturing noise and outliers that don't generalize to new, unseen data.

__Non-Robust to Outliers__

Decision trees can be sensitive to outliers. Outliers can have a significant impact on the structure of the tree, leading to suboptimal splits.

__Not Suitable for Linear Relationships__

Decision trees are not well-suited for capturing linear relationships between features. They are inherently non-linear and may require a large number of splits to approximate linear functions.


__Greedy Nature__

Decision trees use a greedy algorithm to make splits, meaning they choose the best split at each step without considering the global optimum. This can lead to suboptimal trees.



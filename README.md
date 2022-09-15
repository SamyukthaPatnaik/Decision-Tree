# Decision-Tree
- Decision Tree is a Supervised learning technique that can be used for both classification and Regression problems, but mostly it is preferred for solving Classification problems. 
- Decision trees use multiple algorithms to decide to split a node into two or more sub-nodes.
- It is a tree-structured classifier, the tree can be explained by two entities, namely decision nodes and leaves, where internal nodes represent the features of a dataset, branches represent the decision rules and each leaf node represents the outcome.
- It is called a decision tree because,it is similar to a tree, it starts with the root node, which expands on further branches and constructs a tree-like structure.
- In order to build a tree, we use the **CART algorithm**, which stands for Classification and Regression Tree algorithm.

 `A decision tree can contain categorical data (YES/NO) as well as numeric data.`
 
**1. Classification trees (Yes/No types)**

What we’ve seen above is an example of classification tree, where the outcome was a variable like ‘fit’ or ‘unfit’. Here the decision variable is Categorical.

**2. Regression trees (Continuous data types)**

Here the decision or the outcome variable is Continuous, e.g. a number like 123. 

![DT](https://365datascience.com/resources/blog/rr6cuudl59r-decision-trees-image1.png)

## Decision Tree Terminologies

**Root Node:** Root node is from where the decision tree starts. It represents the entire dataset, which further gets divided into two or more homogeneous sets.

**Leaf Node:** Leaf nodes are the final output node, and the tree cannot be segregated further after getting a leaf node.

**Splitting:** Splitting is the process of dividing the decision node/root node into sub-nodes according to the given conditions.

**Branch/Sub Tree:** A tree formed by splitting the tree.

**Pruning:** Pruning is the process of removing the unwanted branches from the tree.

**Parent/Child node:** The root node of the tree is called the parent node, and other nodes are called the child nodes.

## A Practical Example

![Example](https://365datascience.com/resources/blog/59utffqewug-decision-trees-image2.png)

## For More Examples- Refer
1. [365datascience](https://365datascience.com/tutorials/machine-learning-tutorials/decision-trees/)
2. [xoriant](https://www.xoriant.com/blog/decision-trees-for-classification-a-machine-learning-algorithm)
3. [towardsdatascience](https://towardsdatascience.com/decision-trees-in-machine-learning-641b9c4e8052)




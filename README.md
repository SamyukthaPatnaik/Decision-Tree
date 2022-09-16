# Decision-Tree
- Decision Tree is a Supervised learning technique that can be used for both classification and Regression problems, but mostly it is preferred for solving Classification problems. 
- Decision trees use multiple algorithms to decide to split a node into two or more sub-nodes.
- It is a tree-structured classifier, the tree can be explained by two entities, namely decision nodes and leaves, where internal nodes represent the features of a dataset, branches represent the decision rules and each leaf node represents the outcome.
- It is called a decision tree because,it is similar to a tree, it starts with the root node, which expands on further branches and constructs a tree-like structure.
- In order to build a tree, we use the **CART algorithm**, which stands for Classification and Regression Tree algorithm.

 `A decision tree can contain categorical data (YES/NO) as well as numeric data.`
 
**1. Classification trees (Yes/No types)**

A practical example of classification tree is given below, where the outcome was a variable like ‘yes’ or ‘no’. Here the decision variable is Categorical.

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

**Note:**

**1.** There could be more than one tree that fits the same data.

**2.** We can't randomly choose the root node.

## Decision tree splitting methods

1. [Entropy](https://analyticsindiamag.com/a-complete-guide-to-decision-tree-split-using-information-gain/)
2. [Gini Index](https://analyticsindiamag.com/understanding-the-maths-behind-the-gini-impurity-method-for-decision-tree-split/#:~:text=Gini%20impurity%20is%20an%20important%20measure%20used%20to%20construct%20the%20decision%20trees.&text=Gini%20impurity%20is%20a%20function,values%20from%200%20to%200.5.)

## When to stop slitting?
- As a problem usually has a large set of features, it results in large number of split, which in turn gives a huge tree. Such trees are complex and can lead to overfitting
- One way is to set a minimum number of training inputs to use on each leaf.
- Another way is to set maximum depth of your model (Maximum depth refers to the the length of the longest path from a root to a leaf).

**[Pruning-](https://en.wikipedia.org/wiki/Decision_tree_pruning#:~:text=Pruning%20is%20a%20data%20compression,and%20redundant%20to%20classify%20instances.)**

- The performance of a tree can be further increased by pruning. It involves removing the branches that make use of features having low importance. 
- This way, we reduce the complexity of tree, and thus increasing its predictive power by reducing overfitting.
- Pruning can start at either root or the leaves.
- The simplest method of pruning starts at leaves and removes each node with most popular class in that leaf, this change is kept if it doesn't deteriorate accuracy.

## For More Examples- Refer
1. [365datascience](https://365datascience.com/tutorials/machine-learning-tutorials/decision-trees/)
2. [xoriant](https://www.xoriant.com/blog/decision-trees-for-classification-a-machine-learning-algorithm)
3. [towardsdatascience](https://towardsdatascience.com/decision-trees-in-machine-learning-641b9c4e8052)




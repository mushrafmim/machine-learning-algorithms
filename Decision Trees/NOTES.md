# Decision Trees

Decision Trees can perform both classification and regression.
This is the fundamental components of random forests.

## Pros

Needs very little data preperation. No feature scaling or centering needed.

Easily understandable by humans unlike Neural Networks or Random Forests.

## Gini impurity

Gini impurity decides the purity of a node.

if gini = 0 then the class is pure.

Gini impurity is calculated using.

$$
G_i = 1 - \sum_{k=1}^{n} p_{i,k}^2
$$

For example,

consider an outcome having 3 classes and in a node you get an outcome of [4, 34, 10].

Total outcomes = 4 + 34 + 10 = 50

So, the impurity for that node is,

$$
G_i = 1 - \left( \frac{4}{50} \right)^2 - \left( \frac{34}{50} \right)^2 - \left( \frac{10}{50} \right)^2
= 0.4912
$$

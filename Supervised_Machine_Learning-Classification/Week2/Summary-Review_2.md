# Summary/Review

The main idea behind support vector machines is to find a hyperplane that separates classes by determining decision boundaries that maximize the distance between classes.

When comparing logistic regression and SVMs, one of the main differences is that the cost function for logistic regression has a cost function that decreases to zero, but rarely reaches zero. SVMs use the Hinge Loss function as a cost function to penalize misclassification. This tends to lead to better accuracy at the cost of having less sensitivity on the predicted probabilities.

Regularization can help SVMs generalize better with future data.

By using gaussian kernels, you transform your data space vectors into a different coordinate system, and may have better chances of finding a hyperplane that classifies well your data.SVMs with RBFs Kernels are slow to train with data sets that are large or have many features.  
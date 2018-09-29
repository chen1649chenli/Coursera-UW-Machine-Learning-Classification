# Coursera-UW-Machine-Learning-Classification

Course can be found in [Coursera](https://www.coursera.org/learn/ml-classification)

- Week 1:
  - Linear Classifiers & Logistic Regression
    - decision boundaries
    - linear classifiers
    - class probability
    - logistic regression
    - impact of coefficient values on logistic regression output
    - 1-hot encoding
    - multiclass classification using the 1-versus-all
- Week 2:
  - Learning Linear Classifiers
    - Maximum likelihood estimation
    - Gradient ascent algorithm for learning logistic regression classifier
    - Choosing step size for gradient ascent/descent
    - (VERY OPTIONAL LESSON) Deriving gradient of logistic regression
  - Overfitting & Regularization in Logistic Regression
    - Overfitting in classification
    - Overconfident predictions due to overfitting
    - L2 regularized logistic regression
    - Sparse logistic regression
- Week 3:
  - Decision Trees
    - Predicting loan defaults with decision trees
    - Learning decision trees
        - Recursive greedy algorithm
        - Learning a decision stump
        - Selecting best feature to split on
        - When to stop recursing
    - Using the learned decision tree
        - Traverse a decision tree to make predictions: Majority class predictions; Probability predictions; Multiclass classification
    - Learning decision trees with continuous inputs
        - Threshold splits for continuous inputs
        - (OPTIONAL) Picking the best threshold to split on
- Week 4
  - Overfitting in decision trees
    - Identify when overfitting in decision trees
    - Prevent overfitting with early stopping
      - Limit tree depth
      - Do not consider splits that do not reduce classification error
      - Do not split intermediate nodes with only few points
    - Prevent overfitting by pruning complex trees
      - Use a total cost formula that balances classification error and tree complexity
      - Use total cost to merge potentially complex trees into simpler ones
  - Handling missing data
    - Describe common ways to handling missing data:
      1. Skip all rows with any missing values
      2. Skip features with many missing values
      3. Impute missing values using other data points
    - Modify learning algorithm (decision trees) to handle missing data:
      1. Missing values get added to one branch of split
      2. Use classification error to determine where missing values go
- Week 5
  - Boosting
    - Identify notion ensemble classifiers
    - Formalize ensembles as the weighted combination of simpler classifiers
    - Outline the boosting framework – sequentially learn classifiers on weighted data
    - Describe the AdaBoost algorithm
      - Learn each classifier on weighted data
      - Compute coefficient of classifier
      - Recompute data weights
      - Normalize weights
    - Implement AdaBoost to create an ensemble of decision stumps
    - Discuss convergence properties of AdaBoost & how to pick the maximum number of iterations T
- Week 6
  - Evaluating classifiers: Precision & Recall
    - Classification accuracy/error are not always right metrics
    - Precision captures fraction of positive predictions that are correct
    - Recall captures fraction of positive data correctly identified by the model
    - Trade-off precision & recall by setting probability thresholds
    - Plot precision-recall curves.
    - Compare models by computing precision at k
- Week 7
  - Scaling to Huge Datasets & Online Learning
    - Significantly speedup learning algorithm using stochastic gradient
    - Describe intuition behind why stochastic gradient works
    - Apply stochastic gradient in practice
    - Describe online learning problems
    - Relate stochastic gradient to online learning 

# [Machine Learning with Andrew Ng](https://www.coursera.org/learn/machine-learning) 

This repository contains my completed assignments of Andrew Ng's now classic machien learning course on Coursera, in Python instead of the original MATLAB, which serves as a broad introduction to machine learning. This course has since been adapted into a three-part series comprising the [Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction).


## 1. [Linear Regression](/Exercise1/exercise1.ipynb)

- Performed Z-Score __normalization__ on featuress
- Solved linear regressions using **gradient descent** as optimizer
- Compared results to closed-form solutions based on normal equations
- Visualized cost function on surface and contour plots.

![Cost function plots](/Exercise1/Figures/cost_function.png)

## 2. [Logistic Regression](/Exercise2/exercise2.ipynb)

- Constructed **logistic regression** with **sigmoid function** as the cost function
- Performed **polynomial feature mapping** to account for nonlinearity in data
- Added **L2 regularization** to control the risk for overfitting as a result of feature mapping
- Implemented gradient descent with `scipy.optimize.minimize`

![Decision boundary with regularization](/Exercise2/Figures/decision_boundary2.png)



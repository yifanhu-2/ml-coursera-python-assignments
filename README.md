# [Machine Learning with Andrew Ng](https://www.coursera.org/learn/machine-learning) 

This repository showcases my journey through Andrew Ng's now classic machine learning course on Coursera, in Python instead of the original MATLAB. As a quantitative researcher coming from a background in experimental statistics, I got to expand my technical repertoire into statistical learning. The course has since been adapted into a three-part series comprising the [Machine Learning Specialization](https://www.coursera.org/specializations/machine-learning-introduction).


## 1. [Linear Regression](/Exercise1/exercise1.ipynb)

- Performed Z-Score *normalization* on featuress
- Solved linear regressions using **gradient descent** as optimizer
- Compared results to closed-form solutions based on normal equations
- Visualized cost function on surface and contour plots.

![Cost function plots](/Exercise1/Figures/cost_function.png)

## 2. [Logistic Regression](/Exercise2/exercise2.ipynb)

- Created a **logistic regression** with **sigmoid function** as the cost function
- Performed **polynomial feature mapping** to account for nonlinearity in data
- Added **L2 regularization** to control the risk for overfitting as a result of feature mapping
- Implemented gradient descent with `scipy.optimize.minimize`

![Decision boundary with regularization](/Exercise2/Figures/decision_boundary2.png)

## 3. [Multi-class Classification](/Exercise3/exercise3.ipynb)

- Implemented one-vs-all logistic regression with L2 regularization using gradient descent
- Based on a 5000 example subset from the [MNIST](http://yann.lecun.com/exdb/mnist/) handwritten digit dataset

![Cost function plots](/Exercise3/Figures/output.png)

## 4. [Neural Networks with Backpropagation](/Exercise4/exercise4.ipynb)

- Created a simple neural network (NN) with 1 hidden layer, built on logistic regression with sigmoid activation, with L2 regularization
- Initialized with random weights
- Implemented **backpropagation** and **gradient checking**

![Simple NN plots](/Exercise4/Figures/ex4-backpropagation.png)

## 5. [Bias vs Variance Trade-off](/Exercise5/exercise5.ipynb)

- Created a polynomial NN with 1 hidden layer with sigmoid activation
- Plotted **learning curve** for train and cross-validation samples to gauge fitness, and **validation curve** for diagnostics
- Tackled the overfitting problem by experimenting with different levels of regularization

| Polynomial fit | Learning Curve | Validation Curve |
| --- | --- | --- |
| ![Poly fit](/Exercise5/Figures/polynomial_regression.png) | ![LC](/Exercise5/Figures/polynomial_learning_curve.png) | ![VC](/Exercise5/Figures/cross_validation.png) |

## 6. [Support Vector Machines](/Exercise6/exercise6.ipynb)

- Created a **Gaussian kernel** to learn a nonlinear boundary with SVM
- Optimized for C and RBF parameter sigma through **grid search**
- Trained a linear SVM on a subset of the [SpamAssassin Public Corpus](http://spamassassin.apache.org/old/publiccorpus/)
- Performed **data cleaning**, **vocab building**, and **feature extraction** on emails

![SVM](/Exercise6/Figures/svm_dataset3_best.png) 

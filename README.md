# Introduction to TensorFlow Basics

The following files give a brief 101 intro to TensorFlow. These files were created together for my Introduction to TensorFlow lecture.

## basic_op.py
This file defines some basic operations, setting of constants, variables and operator nodes. It also introduces building a simple model and running a TensorFlow session to run the model.

## linear_regression.py
Here we make a simple linear regression using the murder_rates_data.csv dataset to plot training and testing data on a linear regression. We also add TensorBoard summaries to the code which can then be run using `tensorboard --logdir="/logs"`
![Output of Linear Regression](https://github.com/skydev111/TensorFlow-introduction/main/output_linear_regression.PNG "Output of Linear Regression")


## logistic_regression.py
Here we expand on the linear regression model and build a logisitic (softmax) regression for the MNIST dataset. The output also includes a nice visual output from two test cases using matplotlib

![Output of Logistic Regression](https://github.com/skydev111/TensorFlow-introduction/main/output_logistic_regression.PNG "Output of Logistic Regression")
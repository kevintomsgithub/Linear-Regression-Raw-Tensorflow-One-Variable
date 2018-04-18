# Linear-Regression-Raw-Tensorflow

Builds a simple raw linear regression model with basic tensorflow

# Libraries Required

1. numpy.      # install by : pip install numpy
2. tensorflow. # install by : pip install tensorflow
3. matplotlib  # install by : pip install matplotlib or sudo apt-get install matplotlib

# Overview

This is a simple tutorial program which has been developed, focusing on those who are beginners to Machine Learning and Tensorflow, the code snippet has been commented with lots of information.. please go through it..
- A bit of a recall, during school times, in Linear algebra we have come accross the mathematical equation for a straight line ie, y = m*x + c, we work around with the same formula in this program too..

# Training data

- when x = 1 some calculation done on 'x' and 'y' was predicted as 2. !!
- when x = 2 some calculation done on 'x' and 'y' was predicted as 3. !!
- when x = 3 some calculation done on 'x' and 'y' was predicted as 4. !!
- .. ..
- .. ..

so from the above its clear that adding 1 to 'x's gives 'y's ie,
when x=1,
-  y = 1 + 1 = 2,
-  y = m * x + c
-  x = 1
-  m = 1
-  c = 1
-  therefore, y = 1 * 1 + 1 = 2

So, what we have with us is the training data, and testing data for validating the training, the aim of this program is to find the values for 'm' and 'c' which is 'W'(weight) and 'b'(bias) respectively.

# Solution

And thus finding the values of 'W' and 'b', and substituting them to the above equation y = W * X + b, gives the vaue of y for any substituion of 'X' in it.

# Challenge - tweek

Tweek some parameter to obtain close results, by reducing the cost function and precising the values for Weights and Bias.
Please keep me posted for any doubts and updates.

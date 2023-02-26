# Two Linear Regression Problem
## problem1:
Implementing Normal Equation in Linear Regression: \
$f(x;w) = y_{hat} = w_0+w_1x$ \
$W = (X^{T}X)^{-1}X^{T}Y$ 

Implementing Normal Quintic Equation: \
$f(x;w) = y_{hat} = w_0+w_1x^1+w_2x^2+w_3x^3+w_4x^4+w_5x^5$

On the 10th first, 25th first, 50 first, 100th first and whole data: \
![image](https://user-images.githubusercontent.com/83788223/221396599-d8d353a4-62b0-4f6f-8b91-77850001adfc.png)

MSE: \
![image](https://user-images.githubusercontent.com/83788223/221396732-d29ed541-f0db-4da5-b57d-15fba710b92a.png)

## problem2:
linear equation, quintic equation and cubic equation regression:

Standardization: \
$X_{standard} = (X-E[X]) / \sqrt(var(X))$ \
$E[X] = (1/n)\sum x = mean(X)$ \
$var(X) = E[(x-E[X])^2] = (1/n)\sum(x_i-mean(X))^2$ 

Normal-Based Regression With Regularization: \
$W = (X^{T}X+\lambda I)^{-1}X^{T}Y$

implementing 5-fold cross-validation and running 10 times for parameter lambda = 0, 1, and 1: \
![image](https://user-images.githubusercontent.com/83788223/221397074-90d53949-b631-4729-9fbb-28561e6587b0.png)

![image](https://user-images.githubusercontent.com/83788223/221397113-d4f452c9-7754-4829-ba0f-7e7194a71961.png)



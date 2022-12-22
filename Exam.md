# Exam solutions

### 16. Why it is not recommended to initialize all the weights in NN with 0?

There are two main reasons for this:

* We can easily get stuck if $(0,0,0,..)$ is local minimum.
* Under the assumptions that all the neurons has the same weight: all nodes will follow almost the same gradient which will finish in impossibility of good training.

### 4. Compare properties of the solutions of linear regression with MSE loss and 2-layer perceptron for regression task without activation function $y = XW_1W_2$.

The ban of using the activation function makes these two models almost the same because if the perceptron had the activation function there would be some non-linearity included.

However 2-layer perceptron is just 2 applies of some linear equations. This makes $W_1W_2 = W$ the best solution. So there is almost no difference. Only the gradient will fade out and maybe give perceptron some mistake.

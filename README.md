# Linear Regression From Scratch
The purpose of this project is to run a linear regression algorithm on Employee data to predict salary.
As implied by the title, this project does not utilize any machine learning packages (such as: Scikit-Learn, TensorFlow, or PyTorch).


The Data can be found here: [kaggle.com](https://www.kaggle.com/code/vivinbarath/simple-linear-regression-for-salary-data/input)

### Loss
The Linear Regression Model makes use of a simple Mean Squared Error (MSE) Loss function:
$MSE = \frac{1}{2n}\sum{n}(\hat{y}-y)$

### Training
Paramter vector $\theta$ is chosen at random and the linear regression model undergoes gradient descent for 120,000 epochs until convergence at the optimal $\theta$ vector.

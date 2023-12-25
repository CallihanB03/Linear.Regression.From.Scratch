# Linear Regression From Scratch
The purpose of this project is to run a linear regression algorithm on Employee data to predict salary.
As implied by the title, this project does not utilize any machine learning packages (such as: Scikit-Learn, TensorFlow, or PyTorch).


The Data can be found here: [kaggle.com](https://www.kaggle.com/code/vivinbarath/simple-linear-regression-for-salary-data/input)

## Loss
The Linear Regression Model makes use of a simple Mean Squared Error (MSE) Loss function:
$MSE = \frac{1}{2n}\sum_{n}(\hat{y}-y)^{2}$

## Training
Paramter vector $\theta$ is chosen at random and the linear regression model undergoes gradient descent for 120,000 epochs until convergence at the optimal $\theta$ vector.

<img width="908" alt="Screenshot 2023-12-25 at 14 35 48" src="https://github.com/CallihanB03/Linear.Regression.From.Scratch/assets/123860294/ca117fd9-4315-422e-9d2b-3977c46398f4">

## Evaluation
Model evaluated on testing data

<img width="646" alt="Screenshot 2023-12-25 at 14 48 45" src="https://github.com/CallihanB03/Linear.Regression.From.Scratch/assets/123860294/6bfc1f9d-f102-4832-b7d4-7e90b27134c4">

# Conclusions
The linear regression model does is able to find the optimal $\theta$ vector for predicting salary from employee data.

## Liminations
* The dataset used for this training is very small and, as a result, results may lose interpretability.
* The gradient is scaled down to very a low value in order to have a more accurate model meaning that the algorithm trains for a significantly large number of epochs then it would need to train for if it was aiming for slightly less accuracy. The model trades off efficiency for accuracy.

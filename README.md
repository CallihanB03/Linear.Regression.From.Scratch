# Linear Regression From Scratch
The purpose of this project is to run a linear regression algorithm on Employee data to predict salary.
As implied by the title, this project does not utilize any machine learning packages (such as: Scikit-Learn, TensorFlow, or PyTorch).


The Data can be found here: [kaggle.com](https://www.kaggle.com/code/vivinbarath/simple-linear-regression-for-salary-data/input)

### Loss
The Linear Regression Model makes use of a simple Mean Squared Error (MSE) Loss function:
<img width="379" alt="Screenshot 2023-12-25 at 14 38 11" src="https://github.com/CallihanB03/Linear.Regression.From.Scratch/assets/123860294/aeb479a5-f2c0-46b7-ac61-586d9d84a0fd">

### Training
Paramter vector $\theta$ is chosen at random and the linear regression model undergoes gradient descent for 120,000 epochs until convergence at the optimal $\theta$ vector.

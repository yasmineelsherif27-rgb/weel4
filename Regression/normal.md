Normal Equation

The Normal Equation is a mathematical formula used in Linear Regression to find the best values of the model parameters without using iterative optimization methods like Gradient Descent.

It directly calculates the optimal parameters that minimize the cost function.

Normal Equation Formula
θ=(XTX)−1XTy
θ=(X
T
X)
−1
X
T
y

Where:

θ (theta) = parameters of the model

X = feature matrix (input data)

Xᵀ = transpose of matrix X

(XᵀX)⁻¹ = inverse of the matrix

y = output values (target variable)

Purpose of the Normal Equation

The normal equation is used to calculate the optimal parameters for linear regression that minimize the Mean Squared Error (MSE).

It finds the best fitting line for the data.

Advantages

No need for iterations

No learning rate required

Direct mathematical solution

Disadvantages

Computationally expensive with very large datasets

Requires matrix inversion which may be slow for large feature sets

Example Use

If we have a dataset:

X → features (input variables)

y → target values

We can apply the Normal Equation to calculate the parameters θ that give the best prediction model
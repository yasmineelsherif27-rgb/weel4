Mathematics/calculus.md

Calculus for Machine Learning
Introduction

Calculus is a branch of mathematics that studies how functions change.
It is very important in Machine Learning because it helps optimize models and minimize errors.

In ML, calculus is mainly used in:

Optimization

Gradient Descent

Training models

Function

A function describes the relationship between input and output.

Example:

f(x) = x²

If:

x = 2

Then:

f(2) = 4
Derivative

The derivative measures the rate of change of a function.

It tells us how much the output changes when the input changes.

Notation:

f'(x)

or

df/dx

Example:

f(x) = x²

Derivative:

f'(x) = 2x
Basic Derivative Rules
Constant Rule

Derivative of a constant is zero.

Example:

d/dx (5) = 0
Power Rule

If:

f(x) = xⁿ

Then:

f'(x) = n x^(n-1)

Example:

f(x) = x³

Derivative:

f'(x) = 3x²
Sum Rule

Derivative of sum:

d/dx (f + g) = f' + g'

Example:

f(x) = x² + x

Derivative:

f'(x) = 2x + 1
Partial Derivative

When a function has multiple variables.

Example:

f(x,y) = x² + y²

Partial derivatives:

∂f/∂x = 2x
∂f/∂y = 2y
Gradient

The gradient is a vector containing partial derivatives.

Example:

∇f = [ ∂f/∂x , ∂f/∂y ]

Gradient shows the direction of maximum increase.

Gradient Descent

Gradient Descent is an optimization algorithm used in Machine Learning to minimize error.

Steps:

Start with random parameters.

Compute gradient.

Update parameters.

Repeat until error is minimized.

Update rule:

θ = θ − α ∇J(θ)

Where:

θ = parameters
α = learning rate
∇J = gradient of cost function
Importance of Calculus in Machine Learning

Calculus helps in:

Training models

Finding optimal parameters

Minimizing loss functions

Understanding gradient descent
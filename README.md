# Complete_Gradient_Descent
Gradient Descent is an optimization algorithm used in Machine Learning and Deep Learning to minimize the error (loss) of a model. It works by repeatedly adjusting the model's parameters in the direction that reduces the loss function the most.

Simple Explanation

Imagine you are standing on top of a hill and want to reach the lowest point in the valley. You take small steps downhill, checking the slope each time. Gradient Descent does the same thing mathematically to find the best model parameters.

How it Works
Initialize model parameters randomly.
Calculate the loss (error).
Compute the gradient (slope) of the loss function.
Update parameters using:
θ=θ−α
∂θ
∂J(θ)
	​


Where:

θ = model parameter (weight)
α = learning rate (step size)
J(θ) = loss function
∂J(θ)/∂θ = gradient of the loss
Types of Gradient Descent
Batch Gradient Descent – Uses the entire dataset for each update.
Stochastic Gradient Descent (SGD) – Updates parameters using one training example at a time.
Mini-Batch Gradient Descent – Uses a small batch of data; most commonly used in practice.
Applications
Linear Regression
Logistic Regression
Neural Networks
Deep Learning models

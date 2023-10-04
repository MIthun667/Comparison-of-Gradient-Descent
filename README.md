# Comparison-of-Gradient-Descent
Comparison of Gradient Descent Techniques in Linear Regression

1. Batch Gradient Descent:

* Overview: Uses the entire dataset to calculate the gradient of the loss function. It provides a stable convergence and produces a deterministic path towards the minimum. However, for large datasets, it can be computationally expensive due to the requirement to use all data for each update.

2.Stochastic Gradient Descent (SGD):

* Overview: Uses a single randomly selected data point to compute the gradient in each iteration. It's computationally faster and can escape local minima due to its noisier gradient. However, this noise also means that SGD will never settle at the minimum. Often, a decaying learning rate is used to reduce fluctuations.

3. Mini-batch Gradient Descent:

* Overview: A compromise between Batch and SGD. It uses a mini-batch of samples (typically 32, 64, or 128 samples) to compute the gradient. It benefits from both the computational efficiency of using random samples and the stability of using more than one data point. It's one of the most commonly used optimization methods in deep learning.

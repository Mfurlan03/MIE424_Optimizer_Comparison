# Optimizer Comparison on MNIST

This project investigates how different optimization algorithms affect the solutions learned by neural networks.

We compare SGD, Adam, and RMSprop on the MNIST dataset under a controlled setup, analyzing:
- Training loss (convergence)
- Test accuracy
- Weight norms

Experiments are repeated across multiple random seeds to evaluate stability.

## How to run

1. Install dependencies:
   pip install torch torchvision matplotlib numpy

2. Run:
   Optimizer Comparison on MNIST.ipynb

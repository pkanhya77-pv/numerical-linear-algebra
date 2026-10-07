# Numerical Linear Algebra

This repository contains implementations and computational experiments in Numerical Linear Algebra using Python and MATLAB.

My primary interests include:

- Eigenvalue problems
- Backward error analysis
- Structured matrices
- Least-squares problems
- Matrix optimization
- Numerical methods for linear algebra

## Projects

### 1. Backward Error of an Approximate Eigenpair

Given a matrix $A$, an approximate eigenvalue $\lambda$, and an approximate eigenvector $x$, the residual is

$$
r = Ax - \lambda x.
$$

The absolute normwise backward error with respect to perturbations in the matrix $A$ is

$$
\eta = \frac{\|Ax-\lambda x\|_2}{\|x\|_2}.
$$

A minimum-norm perturbation satisfying

$$
(A+\Delta A)x = \lambda x
$$

is

$$
\Delta A = -\frac{r x^T}{x^T x}.
$$

The corresponding Python implementation will be available in the `backward-error` directory.

## Tools

- Python
- NumPy
- MATLAB

## Future Topics

More numerical linear algebra algorithms and computational experiments will be added, including:

- Structured eigenvalue problems
- Matrix conditioning
- Least-squares methods
- Optimization
- Structured matrices
- Backward error analysis

## Author

Prince Kanhya

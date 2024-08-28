# **Statistical Learning Theory**

# **Markov Chain Monte Carlo Sampling**
This project contains implementations of Markov Chain Monte Carlo (MCMC) sampling methods described in [1], which are used to solve the following problems:
- Image reconstruction: denoising a binary image is achieved by minimizing an energy function derived from the Ising model (see [2], Section 8.3.3). Maximum A Posteriori (MAP) inference is used to recover the most likely original image from a noisy input.
- Traveling Salesman Problem: The TSP is solved using MCMC techniques to find the optimal route that minimizes the total distance traveled by a salesman visiting a set of cities exactly once.
![mcmc_sampling](./images/mcmc_sampling.png)

# **References**
[1] [**An Introduction to MCMC for Machine Learning**](http://www.cs.princeton.edu/courses/archive/spr06/cos598C/papers/AndrieuFreitasDoucetJordan2003.pdf)
[2] Bishop, Christopher M. "Pattern Recognition and Machine Learning." (2006).

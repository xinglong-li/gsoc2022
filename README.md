# GSoC 2022 Summary

I participated in [Google Summer of Code 2022](https://summerofcode.withgoogle.com/) as a contributor in the past summer,
and I worked with [Kevin P. Murphy](https://www.cs.ubc.ca/~murphyk/) on the [PyProbML] repo, which is used for the textbook 
"Probabilistic Machine Learning: Advanced Topics".

My work can be roughly separated into two parts.
In the first part, I wrote demos and short sections for the textbook.
In the second part, I mainly contribute to the ssm-jax package.

## 1. Work on the [text book](https://probml.github.io/pml-book/book2.html)

In the first two months I mainly focused on the text book 

- Write demos of [Dirichlet process mixture model for clustering](https://github.com/probml/pyprobml/blob/master/notebooks/book2/31/dp_mixgauss_cluster.ipynb)

- Write subsections on Variational inference of DP mixture model

## 2. Work on the ssm-jax package

This is packagte is about the state space models using jax.

- Write subsections on posteriror inference of state space models using 

- Linear Gaussian dynamics system using [conjugate priors](https://github.com/probml/ssm-jax/blob/main/ssm_jax/linear_gaussian_ssm/models/linear_gaussian_ssm_conjugate.py).

- Add learning algorithms for general [LGSSM models](https://github.com/probml/ssm-jax/blob/main/ssm_jax/linear_gaussian_ssm/models/linear_gaussian_ssm.py).
This model is a fundamental framework and can be used in Structural time series model and causal inference. 

## Summary

I am honored to work with Kevin this summer to contribute to the textbook the orginal version of which 
has influenced me a lot. It is also a wonderful experience to collaborate with all members in this project.
The advisors have always been very supportive and willing to help and the members are very enthusiastic. 

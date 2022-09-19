# GSoC 2022 Summary

This summer I participated in [Google Summer of Code 2022](https://summerofcode.withgoogle.com/) as a contributor,
and I worked with [Kevin P. Murphy](https://www.cs.ubc.ca/~murphyk/) on the [PyProbML](https://github.com/probml) repo, 
which is a complement to the textbook ["Probabilistic Machine Learning: Advanced Topics"](https://probml.github.io/pml-book/book2.html).

My work can be roughly separated into two parts.
In the first half of my work, I worked on adding demos and short sections to the textbook.
In the second part, I joined the [ssm-jax](https://github.com/probml/ssm-jax) group and mainly focused on contributing to the ssm-jax package.

# Highlights

## 1. Work on the text book 

- Add demos of [Dirichlet process (DP) mixture model for clustering](https://github.com/probml/pyprobml/blob/master/notebooks/book2/31/dp_mixgauss_cluster.ipynb)

- Add subsections on Variational inference of DP mixture model.

## 2. Work on the ssm-jax package

- Add subsections on learning and inference of state space models to the textbook.

- Add the class Linear Gaussian state space model [(LGSSM)](https://github.com/probml/ssm-jax/blob/main/ssm_jax/linear_gaussian_ssm/models/linear_gaussian_ssm.py) to the ssm-jax package.
This model is a general framework which takes Structural time series models as special cases
and can be further used for causal inference. 

- Add [LGSSM models with conjugate priors](https://github.com/probml/ssm-jax/blob/main/ssm_jax/linear_gaussian_ssm/models/linear_gaussian_ssm_conjugate.py) to the ssm-jax package.



## Summary

I am honored to work with Kevin this summer to contribute to the textbook the orginal version of which 
has influenced me a lot. The advisors in the team of ssm-jax are very supportive and always willing to help.
It is also a wonderful experience to collaborate with all members in this project.
I am inspired by the their enthusiam for the the product we are making together. 

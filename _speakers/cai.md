---
layout: speaker
name: Diana Cai
first_name: Diana
last_name:  Cai
affiliation: Flatiron Institute
talk_title: "Batch and match: score-based approaches for black-box variational inference"
abstract: "Probabilistic modeling is a cornerstone of modern data analysis,
uncertainty quantification, and decision making. A key challenge of
probabilistic inference is computing a target distribution of
interest, which is often intractable. Black-box variational inference
(BBVI) algorithms have become popular due to their ease of application
facilitated by automatic differentiation. Traditionally, BBVI methods
have focused on factorized variational families. However, in many
complex problems, richer variational families are needed to more
accurately quantify uncertainty and model correlations among latent
variables. While methods based on automatic differentiation
variational inference (ADVI) have been used with some richer families,
gradient-based optimization over these families is often plagued by
high-variance gradients and sensitivity to hyperparameters of the
learning algorithms.

In this work, we present \"batch and match\" (BaM), an alternative
approach to classical BBVI that uses a score-based divergence.
Notably, this score-based divergence can be optimized by a closed-form
proximal update for Gaussian variational families with full covariance
matrices. We analyze the convergence of BaM when the target
distribution is Gaussian, and we prove that in the limit of infinite
batch size the variational parameter updates converge exponentially
quickly to the target mean and covariance. We also evaluate the
performance of BaM on Gaussian and non-Gaussian target distributions
that arise from posterior inference in hierarchical and deep
generative models. In these experiments, we find that BaM typically
converges in fewer (and sometimes significantly fewer) gradient
evaluations than leading implementations of BBVI based on KL
divergence minimization. Finally, we conclude with a discussion of
extensions of score-based BBVI to high-dimensional settings, large
data settings, and non-Gaussian variational families based on
orthogonal function expansions.."
bio: "Diana Cai is a research fellow in the Center for
Computational Mathematics at the Flatiron Institute. Her research
spans the areas of machine learning and statistics, and focuses on
developing robust and scalable methods for probabilistic modeling and
inference. Previously, Diana obtained a Ph.D. in computer science at
Princeton University, an M.A. in computer science at Princeton
University, an M.S. in statistics from the University of Chicago, and
an A.B. in computer science and statistics from Harvard University."
website: https://www.dianacai.com/
category: "Invited Speaker"
---

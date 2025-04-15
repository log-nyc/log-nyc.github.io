---
layout: speaker
name: Mark Goldstein
first_name: Mark
last_name: Goldstein
affiliation: New York University
talk_title: "What’s the Score? Denoising Score Matching with Learned and Nonlinear Diffusions"
abstract: "Denoising score matching (DSM) lies at the core of training diffusion-based generative models and estimating dynamics in systems governed by stochastic processes. Traditionally, DSM has been limited to linear Gaussian diffusions with fixed noising schedules, restricting model flexibility and motivating the use of more complex alternatives like Implicit Score Matching (ISM) for nonlinear settings. In this talk, I’ll present two approaches that broaden the scope of DSM. First, I’ll show how we can learn the diffusion process itself—optimizing its parameters to improve both likelihood and sample quality—while still supporting score-based training via a general lower bound, thereby enabling automated exploration of multivariate and auxiliary-variable diffusions. Second, I’ll introduce local DSM for nonlinear diffusions, leveraging local transition kernels and Taylor expansions to estimate scores even when the dynamics are non-Gaussian or analytically intractable. This local DSM objective can optimize ISM more effectively than ISM itself. Together, these tools allow us to move beyond fixed, handcrafted processes and instead learn diffusion models tailored to both generative and scientific applications, incorporating potentially known nonlinear SDEs."
bio: "Mark Goldstein is a PhD candidate in Computer Science at New York University, advised by Rajesh Ranganath. His research focuses on deep generative models, with applications in healthcare and the sciences. A central theme of his work is rethinking foundational choices in diffusion model training and analyzing how these choices affect performance and efficiency. He has studied these models in the contexts of video generation, partial differential equations, and medical imaging. Previously, Mark earned his undergraduate degree in music composition from the New England Conservatory of Music and was a Student Researcher at DeepMind NYC."
website: https://cs.nyu.edu/~mg3479/
category: "Student Speaker"
---

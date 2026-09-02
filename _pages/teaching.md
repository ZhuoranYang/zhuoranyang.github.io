---
layout: page
permalink: /teaching/
title: Teaching
description: 
nav: true
nav_order: 6
---

[//]: # (For now, this page is assumed to be a static description of your courses. You can convert it to a collection similar to `_projects/` so that you can have a dedicated page for each course.)

[//]: # (Organize your courses by years, topics, or universities, however you like!)

### Lecture Notes

Open-source lecture notes for my courses at Yale. These are living documents — updated each time the course is offered.

<style>
/* Equal-height cards in a grid that reflows from four across to one, using
   the theme's own variables so it follows light and dark. */
.notes-grid .card { height: 100%; transition: transform .15s ease, box-shadow .15s ease; }
.notes-grid .card:hover { transform: translateY(-2px); box-shadow: 0 4px 14px rgba(0,0,0,.10); }
.notes-grid .card-body { display: flex; flex-direction: column; }
.notes-grid .card-text { flex-grow: 1; }
.notes-grid .btn { align-self: flex-start; margin-top: auto; }
.notes-grid .term {
  font-size: .78rem; letter-spacing: .04em; text-transform: uppercase;
  color: var(--global-text-color-light); margin-bottom: .35rem;
}
.notes-grid .term .now { color: var(--global-theme-color); font-weight: 600; }
.notes-grid .card-title { font-size: 1.06rem; line-height: 1.35; margin-bottom: .5rem; }
.notes-grid .card-text { font-size: .93rem; }
.notes-grid .btn { white-space: nowrap; }
</style>

<div class="row notes-grid">

<div class="col-md-6 mb-4">
<div class="card">
<div class="card-body">
<p class="term"><span class="now">Fall 2026 &middot; current</span></p>
<h5 class="card-title"><strong>S&DS 265/565: Introductory Machine Learning</strong></h5>
<p class="card-text">Regression and classification, optimization, neural networks, unsupervised and latent-variable models, diffusion, reinforcement learning, and language models.</p>
<a href="https://zhuoranyang.github.io/sds265-notes/" target="_blank" class="btn btn-primary btn-sm">📖 Read Online</a>
</div>
</div>
</div>

<div class="col-md-6 mb-4">
<div class="card">
<div class="card-body">
<p class="term">Spring 2025, 2023</p>
<h5 class="card-title"><strong>S&DS 685: Reinforcement Learning</strong></h5>
<p class="card-text">Graduate-level course on theoretical foundations of RL, covering MDPs, planning, exploration, deep RL, AlphaGo, RLHF, and RLVR.</p>
<a href="https://zhuoranyang.github.io/sds685-notes/" target="_blank" class="btn btn-primary btn-sm">📖 Read Online</a>
</div>
</div>
</div>

<div class="col-md-6 mb-4">
<div class="card">
<div class="card-body">
<p class="term">Fall 2024, 2023, 2022</p>
<h5 class="card-title"><strong>S&DS 431/631: Optimization and Computation</strong></h5>
<p class="card-text">Optimization for ML and data science: convex optimization, gradient methods, diffusion models, transformers.</p>
<a href="https://zhuoranyang.github.io/sds431-notes/" target="_blank" class="btn btn-primary btn-sm">📖 Read Online</a>
</div>
</div>
</div>

<div class="col-md-6 mb-4">
<div class="card">
<div class="card-body">
<p class="term">Spring 2024</p>
<h5 class="card-title"><strong>S&DS 432/632: Advanced Optimization</strong></h5>
<p class="card-text">Advanced optimization theory and algorithms: duality, interior point methods, proximal methods, mirror descent.</p>
<a href="https://zhuoranyang.github.io/sds632-notes/" target="_blank" class="btn btn-primary btn-sm">📖 Read Online</a>
</div>
</div>
</div>

</div>

---

### Courses

#### S&DS 265/565: Introductory Machine Learning (Fall 2026)

[**Course website**](https://zhuoranyang.github.io/sds265-fall26/) — calendar, lecture slides, and demo notebooks that run in Google Colab.  
[**Lecture notes**](https://zhuoranyang.github.io/sds265-notes/) — open-source notes, released chapter by chapter as the term runs.

**Course Description:**

This course is designed for undergraduates and graduate students who want to understand how modern machine learning works, and to be able to build and evaluate these methods themselves. It is an introductory course: the goal is to introduce the basic ideas of machine learning, and to develop each of them far enough that you can implement it, apply it, and see where it fails.

The course is intended for students in Statistics & Data Science, Computer Science, Engineering, and the quantitative sciences, and is useful to graduate students in Economics, SOM, and the Sciences who expect to use these methods in their own research. It is suitable for undergraduates with the appropriate prerequisites, which are linear algebra, multivariate calculus, probability, and programming experience in Python.

**Topics Covered:**

- Linear regression, regularization, and model selection
- Classification: generative models, logistic regression, maximum-margin classifiers, trees and ensembles
- Optimization: gradient descent, its stochastic version, and adaptive methods
- Neural networks: multilayer perceptrons, training, and convolutional architectures
- Unsupervised learning: principal components, clustering, latent variables and EM
- Generative models: autoencoders, variational autoencoders, diffusion, and flow matching
- Reinforcement learning and policy optimization
- Language models: transformers, post-training, and agents

Every lecture ships with a demo notebook that reproduces its figures and runs in the browser through Google Colab.

#### S&DS 431/631: Optimization and Computation (Fall 2024, Fall 2023, Fall 2022)


**Course Description:**  

This course is designed for undergraduates and graduate students in Statistics & Data Science who need to know about optimization and the essentials of numerical algorithm design and analysis. It is an introduction to more advanced courses in optimization. The overarching goal of the course is to teach students how to design optimization algorithms for Machine Learning and Data Analysis (in their own research, as applies to graduate students). The course is useful for graduate students in programs in Economics, SOM, and the Sciences. It is also suitable for undergraduates with the appropriate prerequisites, which are knowledge of linear algebra, multivariate calculus, and probability.

**Topics Covered in Fall 2024 Version:**

In the 2024 version, we cover materials on the optimization & computation aspects of artificial intelligence. Concretely, this course covers the following topics:

- Backpropagation and Automatic Differentiation
- Background on Convex Optimization: Convex Sets, Convex Functions, Convex Optimization Problems
- Gradient Descent and First-Order Methods for Convex Optimization and Deep Learning
- Diffusion Models and Latent Diffusion
- Transformer and a Primer on Mechanistic Interpretability
- Newton and Interior Point Methods


#### S&DS 432/632: Advanced Optimization Techniques (Spring 2024)

**Course Description:**  

This course delves deep into the fundamental theory and algorithms in optimization with a special emphasis on convex optimization and additional advanced topics. We will explore in depth several optimization methods that are suitable for large-scale problems arising in various applications. These algorithms include gradient methods, proximal methods, mirror descent, Nesterov's accelerated methods, ADMM, quasi-Newton methods, stochastic optimization, variance reduction, extragradient methods, as well as some methods developed for nonconvex settings.

**Topics Covered:**
- Review of Basic Convex Analysis
- Duality Theory
- Newton Methods and Interior Point Methods
- First-Order Methods: Gradient Descent, Subgradient Descent, Proximal Methods and Mirror Descent
- Deep Learning: Transformer Models and Implicit Layers

#### S&DS 685: Reinforcement Learning and Sequential Decision Making (Spring 2025, Spring 2023)

**Course Description:**  

There has been a surge of research interest in reinforcement learning recently, fueled by exciting applications of reinforcement learning techniques to various challenging decision-making problems in artificial intelligence, robotics, and natural sciences. Many of these advances were made possible by a combination of innovative use of flexible neural network architectures, modern optimization techniques, and new and classical RL algorithms. However, a systematic understanding of when, why, and to what extent these algorithms work remains active in ongoing research. This course aims to introduce the theoretical foundations of reinforcement learning, with the goal of equipping students with the necessary tools for conducting research.

This graduate-level course focuses on the **theoretical and algorithmic foundations of Reinforcement Learning**. Specifically, there are four main themes of the course:

(a) fundamentals of RL (Markov decision process, planning algorithms, Q-learning and temporal difference learning, policy gradient)

(b) online RL (bandit algorithms, online learning, exploration)

(c) offline RL (off-policy evaluation, offline policy learning)

(d) further topics (multi-agent RL, partial observability).

 
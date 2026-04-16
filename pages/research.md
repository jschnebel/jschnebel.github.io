---
title: Research
permalink: /research/
---

# Research

My research develops algorithms for optimization problems with hierarchical or game-theoretic structure. The common thread is that these problems involve multiple levels or multiple agents: a collection of agents reaches some form of equilibrium at a lower level, and a decision-maker at the upper level optimizes over the resulting equilibrium set. Classical examples include selecting the most efficient traffic equilibrium in a transport network, or choosing regularization parameters in inverse problems where the reconstruction itself solves a variational problem.

The algorithmic challenge is that these problems combine large-scale stochastic structure (the operators are finite sums or expectations) with a nested feasibility constraint (the lower-level equilibrium). I work on extragradient and operator splitting methods that handle both, using variance reduction and Bregman geometry to get provable convergence rates.

## Preprints

- P. Dvurechensky, A. Ebner, J.C. Schnebel, S. Shtern, M. Staudigl, [*Stochastic variance reduced extragradient methods for solving hierarchical variational inequalities*](https://arxiv.org/abs/2602.13510), arXiv:2602.13510, 2026.

  We study hierarchical variational inequalities where both the upper- and lower-level operators have a finite-sum structure. This setting covers equilibrium selection problems, bilevel optimization, and certain adversarial learning formulations. We develop stochastic extragradient methods with SVRG-type variance reduction in both Euclidean and Bregman setups, and establish the first convergence rates and complexity bounds for this problem class.

- D.R. Luke, J.C. Schnebel, M. Staudigl, J. Peypouquet, S. Qu, [*Asymptotic behaviour of coupled random dynamical systems with multiscale aspects*](https://arxiv.org/abs/2601.15411), arXiv:2601.15411, 2026.

  We analyze coupled dynamical systems that evolve on different time scales under stochastic perturbations. This framework captures algorithms that simultaneously regularize (via Tikhonov-type terms) and penalize (to enforce constraints), and provides a unified convergence theory. The results apply to constrained variational inequalities and bilevel problems where the constraint set is itself defined by an equilibrium condition.

## Master thesis

- J. Schnebel, [*First Order Methods for Stochastic Optimal Control with an Application to Microgrid Optimization*](/assets/doc/Masterthesis_JohannesSchnebel.pdf), Mannheim University, 2025.

  The thesis develops and compares first-order optimization methods for multi-stage stochastic optimal control problems arising in microgrid energy management — deciding when to store, consume, or sell electricity under uncertain renewable generation and fluctuating prices.

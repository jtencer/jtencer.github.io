---
permalink: /pubs/CMAME2021/
title: "A Compute-Bound Formulation of Galerkin Model Reduction for Linear Time-Invariant Dynamical Systems"
excerpt: "A Compute-Bound Formulation of Galerkin Model Reduction for Linear Time-Invariant Dynamical Systems"

toc: true
---

Francesco Rizzi, Eric Parish, Patrick Blonigan, and John Tencer  
Preprint  
[View at Publisher](https://www.sciencedirect.com/science/article/pii/S0045782521003042)  
[View Preprint on Arxiv](https://arxiv.org/abs/2009.11742) 

### Abstract

This work aims to advance computational methods for projection-based reduced order models (ROMs) of linear time-invariant (LTI) dynamical systems. For such systems, current practice relies on ROM formulations expressing the state as a rank-1 tensor (i.e., a vector), leading to computational kernels that are memory bandwidth bound and, therefore, ill-suited for scalable performance on modern many-core and hybrid computing nodes. This weakness can be particularly limiting when tackling many-query studies, where one needs to run a large number of simulations. This work introduces a reformulation, called rank-2 Galerkin, of the Galerkin ROM for LTI dynamical systems which converts the nature of the ROM problem from memory bandwidth to compute bound. We present the details of the formulation and its implementation, and demonstrate its utility through numerical experiments using, as a test case, the simulation of elastic seismic shear waves in an axisymmetric domain. We quantify and analyze performance and scaling results for varying numbers of threads and problem sizes. Finally, we present an end-to-end demonstration of using the rank-2 Galerkin ROM for a Monte Carlo sampling study. We show that the rank-2 Galerkin ROM is one order of magnitude more efficient than the rank-1 Galerkin ROM (the current practice) and about 970X more efficient than the full order model, while maintaining excellent accuracy in both the mean and statistics of the field.
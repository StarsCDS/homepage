---
title: "SParSH"
description: "Scalable PARallel numerics for Heterogeneous systems"
slug: ""
image: ""
keywords: ""
categories: 
    - "HPC"
    - ""
date: 2023-07-02T21:27:28+05:30
draft: false
---

## Scalable PARallel numerics for Heterogeneous systems

A Library for Hybrid CPU-GPU Algebraic Multigrid and Preconditioned Iterative Methods

SParSH is hybrid CPU-GPU based solver library featuring parallel Algebraic Multigrid (AMG) solvers and preconditioners for solving large sparse linear system of equations. The library provides implementations of AMG as solver and AMG-preconditioned Krylov subspace solvers for multicore CPU and single node CPU-GPU based computing environments. These implementations utilize hybrid CPU-GPU based approaches to accelerate solving of sparse linear systems. The SParSH package offers flexibility to construct required solver and preconditioner which can be integrated into existing scientific applications.

Key features of library are:

*   Classical (Becks coarsening) , Unsmoothened aggregation and smoothened aggregation based algebraic multigrid
*   OpenMP parallelized implementation of AMG solvers and preconditioner
*   Hybrid CPU-GPU based implementation of AMG solvers and preconditioners
*   Krylov Solvers: CG, GMRES and BiCGStab
*   Smoothers: Jacobi, SOR (currently limited)

Package can be found in following github repository: [https://github.com/cmgcds/SParSH-AMG](https://github.com/cmgcds/SParSH-AMG)

Detailed description of hybrid CPU-GPU approaches can be found in following arXiv paper:   
[SParSH-AMG: A library for hybrid CPU-GPU algebraic multigrid and preconditioned iterative methods](https://arxiv.org/abs/2007.00056)

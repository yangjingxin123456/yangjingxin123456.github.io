---
layout: archive
title: ""
permalink: /research/
author_profile: true
---


# Research interets

1. High-order numerical methods for PDEs:
   - Finite element methods 
   - Discontinuous Galerkin methods
   - Finite difference/volume WENO methods
   - Spectral methods
2. Scientific computing:
   - Parallel implementation of numerical solvers

---


# Projects

## 1. Numerical simulation of plasma equilibrium evolution in nuclear fusion

*Undergraduate Research Program at USTC*

Supervisor: Prof. [Mengping ZHANG](https://dsxt.ustc.edu.cn/zj_ywjs.asp?zzid=860)

July 2021 --- May 2022, USTC

The controlled nuclear fusion is one of the most prospective solution to the energy crisis and environmental problems. The tokamak has been widely investigated as the most feasible magnetically confined fusion device. Tearing mode instabilities have great influence on the fusion reaction thus worth stuying.

In this research, in order to simulate the evolution process of tokamak plasma instability numerically, we reviewed different formulations of the MHD equations, selected a suitable type of nonconservative resistive MHD, and developed a parallel solver using hybrid finite difference-Fourier pseudo spectral method in cylindrical coordinates. Using our solver, we simulated the $(m,n)=(2,1)$ resistive tearing mode instability, and checked the results against those obtained from the CLT and M3D-C1 code with researchers from Institute of Plasma Physics, Chinese Academy of Science. Our solver exhibits satisfactory performance in conserving numerical divergence of the magnetic field, fitting the theoretical relation between logrithmic growth rate of kinetic energy and resistivity, revealing the tearing mode structure independent of initial peturbation at the linear stage, and reaching the final saturation stage.


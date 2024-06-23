---
title: "A new approach for phase field modeling of grain boundaries with strongly nonconvex energy"
collection: publications
permalink: /publication/2019-10-09-gb-anisotropy-msmse
excerpt: ' In this work, we model grain boundary (GB) evolution through phase field approach using additively decoupled regularization scheme utilizing a K23 second order curvature regularization to penalize regions of sharp curvature induced by nonconvex GB energy.'
date: 2019-10-09
venue: 'Modelling and Simulation in Materials Science and Engineering'
paperurl: 'https://doi.org/10.1088/1361-651X/ab47a0'
citation: 'Ribot J.G., Agrawal V. and Runnels B., A new approach to phase field modeling of grain boundaries with strongly nonconvex energy, <i>Modeling and Simulations in Materials Science and Engineering</i>, <b>27</b> (2019), 084007.'
---

Grain boundaries (GBs) are key players in determining macroscopic material behavior and driving the creation of microstructure in nanocrystalline materials. Microstructure typically features irregular features and morphology such as microfaceting, due to the strong nonconvexity of GB energy with respect to boundary plane orientation. Mesoscale simulation of microstructure evolution can be done effectively using the multiphase field (MPF) method. However, strongly nonconvex boundary energies present numerical challenges in MPF simulations. The lack of convexity in GB energy causes the minimal GB energy problem to be mathematically ill-defined. Numerically, this causes mesh dependency and instability. In this work we present an additively decoupled regularization scheme utilizing a K23 second order curvature regularization to penalize regions of sharp curvature induced by nonconvex GB energy. Physically, the K23 regularization corresponds to corner or triple junction dislocations, and does not adversely affect the diffuse properties of the GB or the GB energy. It is shown that the additively decoupled K23 regularization term admits a numerically convenient variational derivative, when evolved in the eigenbasis of the Hessian curvature tensor. This enables K23 to be determined in terms of derivatives in the natural coordinate system, which is advantageous for implementations on a regular grid. The faceting behavior in GBs is demonstrated using a parallel adaptive mesh refinement code. It is shown that faceting is stable even if the GB energy exhibits cusps and the regularization parameter effectively controls the faceting length scale. Evolution of an inclusion is studied for smooth and non-smooth GB energies and results are compared against analytic Wulff shapes. The proposed scheme leverages Lagrange multipliers to use a modified fourth order Allen–Cahn system in lieu of a sixth order Cahn–Hilliard system for numerical efficiency.
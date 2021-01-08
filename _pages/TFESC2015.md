---
permalink: /pubs/TFESC2015/
title: "A Set of Manufactured Solutions for Coupled Radiation (SPn) and Conduction Problems"
excerpt: "A Set of Manufactured Solutions for Coupled Radiation (SPn) and Conduction Problems"

toc: true
---

John Tencer, Tolulope Okusanya, and Adam Hetzler   
ASTFE Thermal and Fluids Engineering Summer Conference 9-12 August 2015 New York City, USA     
[View at Publisher](http://dl.astfe.org/conferences/tfesc,5451756e07e31e0f,6806faa906a55989.html)  

### Abstract

The simplified spherical harmonics (SPn) approximation to the radiative transport equation (RTE) is a computationally efficient deterministic solution method that may be derived either as an asymptotic correction to the diffusion approximation or as a 3D analog to the 1D spherical harmonics (Pn) or discrete ordinates (Sn) approximations. It is used to approximate the effects of participating media radiation. In order to trust the output of a given implementation for a high consequence application, code verification activities must be undertaken to build confidence in the results generated. The method of manufactured solutions is a widely accepted code verification technique in which a solution is assumed and arbitrary source terms are derived such that the code should converge to the prescribed solution. This convergence rate is then confirmed. In this paper we consider the set of coupled PDEs representative of radiation/conduction problems. The RTE is approximated using the "canonical" SPn equations with Mark boundary conditions. All boundaries are diffuse and emissivities range from 0 to 1. A set of manufactured solutions are presented for 1D-planar, 2D-planar, 2D-axisymmetric, and 3D-radially symmetric geometries. These manufactured solutions are used to verify the convergence rate of the conduction and simplified spherical harmonics approximations implemented in Sierra Aria, a highly scalable thermal analysis code.

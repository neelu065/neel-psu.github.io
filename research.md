---
layout: default
title: Projects
group: "navigation"
order: 2
usemathjax: true
summary: A complete list of (co-)authored research.
tags: [Research, Working Paper]
---

# Projects

## Master's Thesis:

**Multimodal Shape Optimization Of NACA0012 Wing With Differential Evolution Based Parallel Niching Algorithm and Reduced‑Order Modeling Technique.**
_Advisor: Dr. DEVENDRA PRAKASH GHATE_

This thesis involves identifying multimodality for the NACA0012 wing (ADODG case‑6 problem). The Differential Evolution (DE) based
niching algorithms (with little or no modification) are implemented on NACA0012 wing to obtain multiple local optima. The mesh
points spread over the NACA0012 airfoil using a cosine distribution function. A Free‑Form Deformation (FFD) box with 60 control
points is set‑up over the NACA0012 wing, which resulted in 125 Dimensional optimization problem. With the help of Principal
Component Analysis (PCA), the problem dimension is reduced to 10 based on its percentage of random energy ( 𝜆2 ). A glyph script
creates the wing tip followed by the volume mesh to all perturbed wings, and the SU2 solver will evaluate for Coefficient of lift (Cl) and Coefficient of drag (Cd). The entire optimization problem carried out in subsonic, inviscid condition (M = 0.4) subjected to several
constraints with reasonably higher residual value. A full‑fledged optimization code written in Python and submitted to the HPC cluster
via SLURM. The python code related to this project can be assessed using GitHub link, Thesis‑codes.
The outcome of the project is as mentioned below.

• A total of four optima are obtained with objective function varying < 8% and a residual value of 10−12.  

• Fine‑tuning of CFD solution is necessary to analyse the work properly.

Due to COVID‑19 pandemic, the computational facility is turned off, which hindered further expansion of the project to the viscous flow
field. The entire thesis can be accessed using the GitHub link as mentioned, Thesis‑file.pdf .

_Tools used_: Pointwise (meshing software), Paraview (Post‑processing software), SU2 (CFD solver), Linux shell script, Python (Constructing framework), SLURM (Submitting jobs to HPC cluster).

## Assisted Projects:

**Aircraft Climb Optimization.**
_Advisor: Dr. DEVENDRA PRAKASH GHATE_

The project focuses on the climb trajectory optimization for aircraft. By finding a feasible and optimal path, it can be proved that
gallons of fuel can be saved, which in turn reduce the cost incurred to the company. There were in total forty‑one design variables, and
the objective was to optimize fuel consumption with several constraints like maximum weight carrying capacity, service ceiling, the
maximum angle of attack, to name a few.

• My role in this project is to make bachelor student understand the Differential Evolution (DE) algorithm and help him to implement the gradient‑free algorithm.


**Variable‑Thrust Optimization of Ascent Trajectory of a Two‑Stage Launch Vehicle.**
_Advisor: Dr. ARAVIND VAIDYANATHAN_

The objective of this project is to optimize the thrust of a two‑stage rocket based on the pitch rate defined at several points along the
trajectory. The problem is defined using 41 variables (Dimension) containing kick rate, and pitch rates defined at equal intervals along
the trajectory. Furthermore, with the 200 initial population, the gradient‑free algorithm (DE) is used to optimize the thrust. The
constraints were that the flight path angle needs to be zero at the orbital height. In this problem, the feasibility rules as proposed by Deb and Saha, for constraints satisfaction is implemented.

• My participation in this project was to set up the problem objective and check for constraint satisfaction in the most efficient way. Python programming is used to set up the entire problem.

## Bachelor's Thesis:

**Experimental Investigation On Conventional Heat pipes Using Various Working Fluid.**
_Advisor: Dr. EZHIL VANNAN S_

The objective of this project is to compare the performance of Heat pipe when subjected to various working fluids. Here, the Aluminium
and Copper pipes of specified dimension are fabricated into Heat pipes with mesh inserted inside the pipes. Working fluids like double
distilled water, acetone, Cupric oxide nanofluid are used. Results are compared by subjecting the Heat pipes to temperature gradient
using a heat source (90 Watts). A comparative study is carried out between straight Heat pipe and the bend Heat pipes.
The outcomes are as follows:

• The rate of heat dissipation depends on working fluids and is maximum for nanofluids.

• The bending of Heat pipe reduces the heat transfer rate due to the increase in the vapour transport resistance.           

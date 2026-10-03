---
layout: default
title: Research
permalink: /research/
---

# Research

My goal is to accelerate large-scale, high-dimensional, and multiscale scientific computation. I develop machine learning algorithms and numerical methods that make challenging simulations faster, more reliable, and scalable.

My research combines structure-preserving learning, uncertainty quantification, molecular–continuum modeling, and multifidelity computation. I rigorously enforce physical and mathematical constraints, quantify predictive uncertainty, and connect models across scales and levels of fidelity. These methods address numerically sensitive problems where conventional learning approaches fail, while reducing the cost of high-fidelity simulation and digital twins.

**My long-term goal is to solve practical industrial problems through collaboration with industry partners. I aim to integrate these computational methods into the design, analysis, and operation of real engineering systems.**

---

## 1. Structure-Preserving Scientific Machine Learning

<figure style="margin: 24px 0; text-align: center;">
  <img
    src="{{ '/assets/images/structure-preserving.png' | relative_url }}"
    alt="Structure-preserving scientific machine learning"
    style="width: 100%; max-width: 900px; height: auto;"
  >
  <figcaption style="margin-top: 10px; font-size: 0.9em; color: #666;">
    Structure-preserving learning for reliable scientific simulations.
  </figcaption>
</figure>

I develop learning algorithms that preserve conservation, symmetry, hyperbolicity, and stability. These algorithms rigorously guarantee physical upper and lower bounds. I tackle challenging simulations where loss-based constraints fail.

**Practical goal:** Accelerate challenging, numerically sensitive, large-scale scientific simulations in nuclear fusion, reactor modeling, and high-energy physics, including high-fidelity radiation hydrodynamics.

**Research Topics**

- Structure-Preserving Learning Algorithms
- Hyperbolic PDE systems
- Entropy Stability and Conservation Laws
- Neural Moment Closures
- Radiation Transport and Hydrodynamics
- Numerical Analysis and Discontinuous Galerkin Methods

---

## 2. Uncertainty Quantification and Propagation in AI

<figure style="margin: 24px 0; text-align: center;">
  <img
    src="{{ '/assets/images/uq.png' | relative_url }}"
    alt="Structure-preserving scientific machine learning"
    style="width: 100%; max-width: 900px; height: auto;"
  >
  <figcaption style="margin-top: 10px; font-size: 0.9em; color: #666;">
    Uncertainty quantification for the Laplace neural operator in predicting the dynamic response of composite structures.
  </figcaption>
</figure>

I develop efficient and robust methods for posterior estimation. I propagate AI model uncertainty through simulations to assess its effect on predicted physical quantities.

**Practical goal:** Quantify how much we can trust AI predictions through uncertainty bounds.

**Research Topics**

- Bayesian Inference and Posterior Estimation
- Generative Models for Inverse Problems
- Ensemble Methods
- Model Uncertainty and Its Propagation
- Predictive Uncertainty Bounds
- Calibration and Validation

---

## 3. Multiscale Simulation

<figure style="margin: 24px 0; text-align: center;">
  <img
    src="{{ '/assets/images/md.png' | relative_url }}"
    alt="Structure-preserving scientific machine learning"
    style="width: 100%; max-width: 900px; height: auto;"
  >
  <figcaption style="margin-top: 10px; font-size: 0.9em; color: #666;">
Molecular simulation of long-chain hydrocarbon combustion.
  </figcaption>
</figure>

I use molecular simulations to study two-phase flows, interfaces, and bubble dynamics where continuum PDE models break down. I develop machine learning models that link molecular behavior to continuum descriptions.

**Practical goal:** Capture molecular effects in scalable continuum simulations.

**Research Topics**

- Molecular Dynamics
- Molecular–Continuum Coupling
- Two-Phase Flows and Bubble Dynamics
- Interfacial Transport and Evaporation
- Vapor–Liquid Equilibrium
- Transcritical and Supercritical Fluids
- Learned Constitutive Relations

---

## 4. Multifidelity Modeling and Adaptive Computation

<figure style="margin: 24px 0; text-align: center;">
  <img
    src="{{ '/assets/images/mf.png' | relative_url }}"
    alt="Structure-preserving scientific machine learning"
    style="width: 100%; max-width: 900px; height: auto;"
  >
  <figcaption style="margin-top: 10px; font-size: 0.9em; color: #666;">
Multifidelity neural operator modeling with uncertainty-guided adaptive selection of high-fidelity samples.
  </figcaption>
</figure>

I combine low- and high-fidelity models. I adaptively select informative simulations and observations to reduce computational and data acquisition costs.

**Practical goal:** Minimize the cost of building accurate AI models and digital twins.

**Research Topics**

- Multifidelity Modeling
- Reduced-Order Modeling
- Operator Learning
- Active Learning and Experimental Design
- Adaptive Sampling and Computation
- Data Assimilation
- Digital Twins

---

## Collaborative Research in Computational Engineering and Physical Sciences

I collaborate with researchers in computational engineering, applied mathematics, and physical sciences to develop and validate methods for challenging multiscale and multiphysics problems. These collaborations connect methodological development with practical simulation.

### 1. Transcritical and Supercritical Fluid Modeling (Purdue University)

In collaboration with the **School of Aeronautics and Astronautics** and the **Department of Mathematics at Purdue University**, I develop machine learning and computational methods for transcritical and supercritical fluids. Research topics include thermodynamic modeling, transport phenomena, molecular dynamics, phase equilibrium, and high-pressure fluid mechanics.

### 2. Radiation Transport and Plasma Modeling (University of Notre Dame)

In collaboration with the **Department of Physics** and the **Department of Aerospace and Mechanical Engineering at the University of Notre Dame**, I develop structure-preserving learning algorithms and numerical methods for radiation transport and plasma modeling. Research topics include hyperbolic systems, moment methods, neural closures, discontinuous Galerkin methods, and data-driven constitutive modeling.

### 3. Molecular Simulation and Transport (Mississippi State University)

In collaboration with researchers at **Mississippi State University** and the **School of Aeronautics and Astronautics at Purdue University**, I develop machine learning methods for molecular simulations and transport phenomena. Applications include evaporation, vapor–liquid equilibrium, mass transport, and surrogate modeling using molecular dynamics data.


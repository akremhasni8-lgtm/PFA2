# PFA2 — Bayesian Optimization Using Mathematica

**End-of-Year Project 2 (PFA2)** — Mechanical Engineering, National Higher
Engineering School of Tunis (ENSIT).

**Authors:** Hasni Akrem & Achouri Ayoub
**Supervisor:** Pr. Ali Trabelsi — **Jury president:** Pr. Ghanem Farhat
**Academic year:** 2025–2026

## Overview

A comprehensive study of machine learning and Bayesian Optimization
implemented end-to-end in the Wolfram Language, applied to mechanical and
manufacturing engineering case studies — culminating in a Bayesian
Optimization workflow for manufacturing process/surface-quality
optimization.

## Report structure

**Chapter I — Machine Learning Paradigms and Fundamentals**
Supervised, unsupervised, and reinforcement learning foundations; empirical
risk minimization; loss functions; the Wolfram Language ML ecosystem.

**Chapter II — Supervised Models**
Applied case studies, including:
- Deflection prediction for simply-supported steel beams
- Rolling-element bearing fault classification
- Weld quality classification using SVM
- 1D Gaussian Process illustration: surface roughness (Ra) vs. feed rate in
  turning (AISI 1045 steel, carbide insert), based on the classical
  Ra ∝ f²/8r relationship
- Fatigue life prediction of steel specimens
- Steel grade classification from chemical composition and heat treatment

**Chapter III — Bayesian Optimization and Gaussian Process Regression**
- Gaussian Process priors/posteriors, covariance function comparison
  (Squared-Exponential, Rational Quadratic, Matérn, etc.)
- Acquisition functions in Bayesian Optimization
- Surface roughness prediction in CNC turning with different GP kernels
  (AISI 4140 alloy steel, coated carbide inserts; cutting speed, feed rate,
  depth of cut as inputs)
- CNC surface-roughness optimization via rotatable Central Composite Design
  (CCD) with 4 process parameters
- Manufacturing case study: 3-axis CNC mill straight-line finish pass
  simulation with touch-probe measurement
- Full 2D Bayesian Optimization convergence study for manufacturing process
  optimization

## Key figures/tables referenced in the report

- Comparison of supervised learning models & evaluation metrics
- Covariance functions and acquisition functions in Wolfram Language
- Manufacturing process optimization workflow diagram
- 2D Bayesian Optimization convergence plot

## Files

```
rapport pfa 2.docx           # full written report (ENSIT template, EN)
presentation exercice.nb     # supporting Mathematica notebook(s)
roughness_2D.xlsx            # CNC surface-roughness dataset
```

## Requirements

- Wolfram Mathematica 14.1+

## Author / Acknowledgements

Hasni Akrem & Achouri Ayoub, Mechanical Engineering, ENSIT. Supervised by
Pr. Ali Trabelsi; jury presided by Pr. Ghanem Farhat.

---
title: "Uncovering heterogeneous effects in computational models for sustainable decision-making"

year: 2024

authors:
  - "Mariia Kozlova"
  - "Robert J. Moss"
  - "Julian Scott Yeomans"
  - "Jef Caers"

venue: "Environmental Modelling & Software"

category: "methodology"

summary: "Introduces an algorithm for the detection of the most important variables, making SimDec fully automatic."

url: "https://doi.org/10.1016/j.envsoft.2023.105898"

---

This paper formalizes heterogeneous effects in computational models and introduces a simple binning algorithm for detecting the most important first- and second-order effects directly from a single Monte Carlo dataset.

By coupling variance-based sensitivity analysis with Simulation Decomposition (SimDec), the procedure makes SimDec fully automatic: the algorithm identifies influential inputs, detects interactions, and selects variables for decomposition without trial-and-error.

The framework is demonstrated on environmental, financial, and sequential decision-making models, and is implemented in open-source packages across Python, R, Julia, and Matlab.

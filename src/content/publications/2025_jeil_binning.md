---
title: "Simple Binning Algorithm and SimDec Visualization for Comprehensive Sensitivity Analysis of Complex Computational Models"
year: 2025
authors:
  - "Mariia Kozlova"
  - "Antti Ahola"
  - "Pamphile Roy"
  - "Julian Scott Yeomans"
venue: "Journal of Environmental Informatics Letters"
category: "methodology"
summary: "Testing and validating the Simple Binning Approach (SBA) for first- and second-order sensitivity indices, and showing why visualization is essential for interpreting interaction effects."
url: "https://doi.org/10.3808/jeil.202400149"
---

This paper formalizes and stress-tests the **Simple Binning Approach (SBA)** for computing variance-based sensitivity indices behind SimDec.

Most global sensitivity analysis studies opt for Saltelli's implementation of Sobol’ indices. SBA follows the original intuition behind variance-based sensitivity:  
bin the input, compute conditional output means, take their variance, normalize.

The paper demonstrates that SBA:

- Requires substantially fewer model evaluations than classic Sobol’ estimators  
- Captures second-order effects directly  
- Works with dependent inputs without transformation  
- Preserves the conservation property (sum of indices ≈ 1)  
- Operates on a single simulation dataset  
- Can be applied to empirical data  

Testing includes:

- The portfolio benchmark model (comparison against Saltelli estimators)
- The Ishigami function (nonlinear periodic behavior)
- High-dimensional multiplicative test models (up to 300 variables)
- An engineering frame model with correlated inputs
- A structural reliability fatigue model (4R method)

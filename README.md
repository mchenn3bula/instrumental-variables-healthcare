# Instrumental Variables Healthcare Analysis 🏥

## Overview 📊
This project applies instrumental variable (IV) methods to the Oregon Health Insurance Experiment to identify the causal effect of health insurance on healthcare outcomes.

## Key Techniques 🔍
- **Instrumental Variables (IV)** estimation
- **Two-Stage Least Squares (2SLS)**
- **Local Average Treatment Effect (LATE)** interpretation
- **Intent-to-Treat (ITT)** analysis
- **Difference-in-Differences** approaches

## Mathematical Framework 🔢
The analysis implements several key concepts:

### IV Estimator
$$\hat{\beta}_{IV} = \frac{Cov(Y,Z)}{Cov(X,Z)}$$

### Local Average Treatment Effect
$$LATE = \frac{E[Y|Z=1] - E[Y|Z=0]}{E[X|Z=1] - E[X|Z=0]}$$

### First-stage and Reduced-form Equations
$$X_i = \alpha_0 + \alpha_1 Z_i + \nu_i$$
$$Y_i = \pi_0 + \pi_1 Z_i + \omega_i$$

## Skills Demonstrated 💪
- Implementation of instrumental variables estimation
- Working with healthcare data
- Understanding of compliance types (always-takers, compliers)
- Distinguishing between correlation and causation
- Advanced econometric modeling
- Statistical inference in complex experimental designs

## Project Significance 🌟
This project showcases the ability to tackle endogeneity problems and selection bias in observational studies, particularly in healthcare policy evaluation where randomized controlled trials are often infeasible or unethical.

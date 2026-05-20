# Grey Wolf Optimizer (GWO) & Advanced Variants

This repository contains the implementation and presentation materials for the **Grey Wolf Optimizer (GWO)**, including its standard version and two advanced variants: **Variable Weight GWO (VW-GWO)** and **Improved Alpha-Guided GWO (IAgGWO)**. 


## 📌 Project Overview
Meta-heuristic search is a dynamic balance between exploration and exploitation. The Grey Wolf Optimizer mimics the leadership hierarchy and hunting mechanism of grey wolves in nature. This repository explores the mathematical foundations of GWO and benchmarks its performance using the **Rastrigin Function** (10 Dimensions).

### Implemented Variants:
1. **Standard GWO**: The classic bio-inspired optimization algorithm.
2. **VW-GWO (Variable Weight GWO)**: Introduces dynamic and iteration-dependent weights to the alpha, beta, and delta wolves to achieve a more effective balance between exploration and exploitation.
3. **IAgGWO (Improved Alpha-Guided GWO)**: Enhances the influence of the alpha wolf as the best current solution using Opposition-Based Learning (OBL) and Gaussian mutation to avoid premature convergence.

## 📁 Repository Structure
* `core/`: Contains the Jupyter Notebook (`Grey wolf.ipynb`) with full implementations, detailed iteration traces, and convergence analysis.


## 📊 Benchmarking & Results
The algorithms are evaluated on the complex, non-linear **Rastrigin Function**. The code generates detailed execution traces for wolf position updates and plots a log-scale convergence comparison showing how each variant optimizes the fitness score over iterations.

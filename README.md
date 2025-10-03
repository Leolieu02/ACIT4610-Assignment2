# Multi-Objective Optimization with NSGA-II and Vega

This repository contains two Jupyter notebooks that demonstrate multi-objective optimization techniques using **NSGA-II** and **Vega**.

## Files

- **NSGA2.ipynb**  
  Implements the **Non-dominated Sorting Genetic Algorithm II (NSGA-II)** for solving multi-objective optimization problems.  
  Includes:
  - Population initialization  
  - Non-dominated sorting  
  - Crowding distance calculation  
  - Selection, crossover, and mutation operators  
  - Example optimization runs with visualizations  

- **Vega copy.ipynb**  
  Implementation of **Vector Evaluated Genetic Algorithm (VEGA)**, one of the earliest genetic algorithms for multi-objective optimization.  
  Includes:
  - Separate fitness evaluation for each objective  
  - Division of the population into subgroups for each objective  
  - Selection and recombination across subgroups  
  - Example optimization runs and visualization of results   

## Requirements

To run the notebooks, install the dependencies:

```bash
pip install numpy matplotlib

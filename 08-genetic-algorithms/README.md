# Genetic Algorithms (GA)

## Objective
Implement and compare genetic algorithm approaches for evolving a random string
toward a target phrase ("ARTIFICIAL INTELLIGENCE"), using both a library
implementation and a from-scratch implementation.

## Topics
- Fitness Functions
- Steady-State Selection
- Single-Point Crossover
- Mutation & Mutation Rate Effects
- Gray Code Encoding
- Elitism

## Libraries
- PyGAD
- NumPy
- Matplotlib

## Files
- GA.ipynb

## Results
Both implementations successfully evolved the target string. Mutation-rate
experiments (0%, 1%, 50%) showed a low mutation rate (1%) reached the target
fastest, no mutation (0%) stalled at a local optimum, and high mutation (50%)
prevented convergence.

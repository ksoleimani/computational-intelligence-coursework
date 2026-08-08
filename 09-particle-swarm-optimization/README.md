# Particle Swarm Optimization (PSO)

## Objective
Implement Particle Swarm Optimization to minimize the 2D Rastrigin function, and
study the effect of individual (cognitive) vs. social weighting on convergence
behavior.

## Topics
- Swarm Initialization
- Velocity & Position Updates
- Personal Best / Global Best
- Rastrigin Function (Multimodal Optimization)
- Cognitive vs. Social Coefficients (C1, C2)

## Libraries
- NumPy
- Matplotlib

## Files
- PSO.ipynb

## Results
The swarm converged to a near-zero global minimum (~6.6e-12). Comparing an
individual-dominant configuration (C1=2.5, C2=0.5) against a social-dominant
configuration (C1=0.5, C2=2.5) showed both reach the global optimum, with the
individual-dominant setting converging slightly faster in early iterations.

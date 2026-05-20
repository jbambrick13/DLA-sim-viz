# Simulating and Visualizing Diffusion Limited Aggregation (DLA) in Python

This project implements a Diffusion Limited Aggregation (DLA) simulation in Python,
developed as part of a Computational Physics course.

DLA is a stochastic process in which particles undergoing Brownian motion randomly
walk until they aggregate, forming complex fractal-like structures seen in nature.

## Models Implemented
- **Inward Growth Model** – Particles spawn at the boundary and walk inward 
  until aggregating with the cluster.
- **Outward Growth Model** – A single seed particle is anchored at the center 
  of the grid and the cluster grows outward over time.

## Key Features
- Monte Carlo simulation of random particle walk and sticking logic
- GIF visualizations of full simulation runs using IPython
- Static final-state visualizations using Matplotlib

## Technologies Used
- Python (NumPy, Matplotlib, IPython)
- Jupyter Notebook (VSCode)

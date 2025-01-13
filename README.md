# Diffusion Limited Aggregation (DLA) Simulation

## Project Overview

This project explores the phenomenon of **Diffusion Limited Aggregation (DLA)**, a process that produces fractal-like structures through the random motion of particles. Using Python, we simulate the DLA process on a lattice and analyze its properties, focusing on the growth rate and the relationship between the height of the structure and the number of particles.

## Features

1. **Simulation of DLA Process**:

   - Implemented a function `dla(W, A, t)` to simulate the aggregation of particles on a rectangular lattice.
   - Visualized the resulting structures using `matplotlib`.

2. **Performance Optimization**:

   - Improved the simulation by dynamically adjusting the starting height of particles based on the current maximum height of the structure.

3. **Growth Rate Analysis**:

   - Investigated the relationship between the time (T) required for a particle to reach a fixed height (H=100) and the width (W) of the lattice.
   - Supported findings with experimental data and visualizations.

## Skills Demonstrated

- **Data Visualization**: Used `matplotlib` to create scatter plots and analyze growth rates.
- **Algorithm Design**: Efficiently implemented and optimized the DLA simulation.
- **Statistical Analysis**: Explored and derived patterns in the simulation results.
- **Scientific Computing**: Worked with large datasets to simulate and analyze physical processes.

## Results

- The simulation successfully replicated the fractal structures characteristic of the DLA process.
- Plots revealed a clear relationship between the growth time (T) and the lattice width (W), supporting the hypothesis about the system's growth dynamics.

## How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/oscar-palomo/diffusion-limited-aggregation.git

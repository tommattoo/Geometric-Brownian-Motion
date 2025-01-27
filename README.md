# Geometric Brownian Motion (GBM) Simulation

## Overview
This project simulates a **Geometric Brownian Motion (GBM)** process, a widely used stochastic model in finance to represent asset price movements over time.

## Model Description
The **GBM** follows the stochastic differential equation:
\[
 dS_t = \mu S_t dt + \sigma S_t dW_t
\]
where:
- \( S_t \) is the asset price at time \( t \)
- \( \mu \) is the drift (expected return)
- \( \sigma \) is the volatility
- \( dW_t \) represents a Wiener process (random noise)

## Implementation
The simulation is implemented in Python using **NumPy** and **Matplotlib**. The model generates multiple stochastic paths and visualizes them over a defined time horizon.

## Features
- Simulates multiple GBM paths.
- Adjustable parameters: \( \mu \), \( \sigma \), time horizon, and time step.
- Visualizes asset price trajectories using Matplotlib.

## Installation
Clone this repository and install the required libraries:
```sh
pip install numpy matplotlib
```

## Usage
Run the script in a Jupyter Notebook or a Python environment:
```python
python gbm_model.py
```

## Next Steps
- Extend the model to include **stochastic volatility (e.g., Heston model)**.
- Compare performance with **Mean-Reverting Processes**.
- Apply the model to real market data for validation.

## License
This project is under the MIT License.

## Author
Tommaso Campi


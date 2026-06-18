# 13-Bus Power System Load Flow Analysis

## Project Overview
This project implements a comprehensive steady-state load flow analysis program on a 13-bus electrical network. It features an analytical mathematical engine built from scratch to calculate grid variables, combined with an assessment of grid-tied solar photovoltaic (PV) integration and line loss minimization.

## Tech Stack
* **Mathematical Modeling & Coding:** MATLAB
* **Network Simulation & Validation:** PowerWorld Simulator

## Implemented Engineering Tasks
* **Numerical Solvers:** Coded the Gauss-Seidel and Newton-Raphson algorithms in MATLAB to solve non-linear power flow equations for unknown bus voltages and phase angles.
* **Renewable Integration:** Modeled grid-tied solar PV generation inputs to map active power injection effects on overall transmission line losses.
* **Industrial Validation:** Reconstructed the complete 13-bus network layout visually in PowerWorld Simulator to verify convergence limits and system-wide reactive power dispatch accuracy.

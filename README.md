# battery-stochastic-control
Python code for stochastic electricity price calibration and stochastic optimal control of a battery energy storage system under electricity market.


This repository contains the Python implementation used for the calibration and optimization procedures presented in the study.

The first part of the code performs electricity price calibration based on historical market data (ENTSO‑E). It estimates the parameters of the stochastic price model and computes confidence intervals for the calibration error.

The second part implements a stochastic optimal control problem for a battery energy storage system. The model integrates battery dynamics and degradation constraints to determine the optimal charging and discharging strategy that minimizes electricity consumption costs.

The full workflow includes data preprocessing, model calibration, simulation of price trajectories, and numerical optimization of the battery control policy.

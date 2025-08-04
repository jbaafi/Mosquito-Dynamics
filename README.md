# Mosquito Population Dynamics Model

This repository contains a simplified version of a climate-driven mosquito population dynamics model. The model uses temperature and rainfall inputs to simulate mosquito life stages over time.

## Features
- Deterministic simulation
- Daily time-step model with determinstic temperature and rainfall
- Visualization of population trajectories over time

## Tools
- R (`deSolve`, `ggplot2`, `dplyr`, `lhs`)
- Simulated climate input data

## Example
To run the model:
```r
Knit("code/model_summary.Rmd")

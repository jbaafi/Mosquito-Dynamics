# Tropical Mosquito Dynamics: A Climate-Driven Model of Anopheles Populations

This repository presents a simplified model of Anopheles mosquito population dynamics under seasonal climatic conditions typical of sub-Saharan Africa. Temperature and rainfall inputs drive the life cycle dynamics across multiple stages.

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

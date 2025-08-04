# Tropical Mosquito Dynamics: A Climate-Driven Model of Anopheles Populations

This repository presents a simplified model of Anopheles mosquito population dynamics under seasonal climatic conditions typical of sub-Saharan Africa. Temperature and rainfall inputs drive the life cycle dynamics across multiple stages.

## Features
- Deterministic simulation
- Daily time-step model with determinstic temperature and rainfall
- Visualization of population trajectories over time

## Tools
- R (`deSolve`, `ggplot2`, `dplyr`, `lhs`)
- Simulated climate input data

## To Run the Model

Open the R Markdown file and click **"Knit"** in RStudio, or run the following in the R console:

```r
rmarkdown::render("code/model_summary.Rmd")

## Repository Structure

project-root/
├── code/ # R Markdown model implementation
├── data/ # Simulated temperature and rainfall input data
├── figures/ # Output plots generated from the model
└── README.md # Project description and usage instructions

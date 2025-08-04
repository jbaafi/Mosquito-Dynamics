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
```

## Repository Structure

```r
project-root/
├── code/ # R Markdown model implementation
├── data/ # Simulated temperature and rainfall input data
├── figures/ # Output plots generated from the model
└── README.md # Project description and usage instructions
```

## Citation

If you use this model or its components in your work, please cite:

Baafi, J. & Hurford, A. (2025). *Modeling the Impact of Seasonality on Mosquito Population Dynamics: Insights for Vector Control Strategies*. Bulletin of Mathematical Biology.

DOI: [10.1007/s11538-024-01409-7](https://doi.org/10.1007/s11538-024-01409-7)

## Author

## Author

**Joseph Baafi**  
PhD Candidate – Mathematical Biology  
Memorial University of Newfoundland  
📧 jbaafi89@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/josephbaafi/)  
🌐 [Website](https://jbaafi.github.io/joseph.baafi/)


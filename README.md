Project Overview

This repository includes scripts and data products used to generate environmental covariates, fit a spatiotemporal Bayesian species distribution model for Mormon cricket, and visualize estimated distribution maps.

1. Environmental Covariate Dataset Generation

File: Dataset_Generate.Rmd
This R Markdown script produces the environmental covariate dataset used for species distribution modeling.
It compiles environmental raster layers and prepares them as model-ready covariates.

2. Bayesian INLA Species Distribution Modeling

File: INLA_Bayesian_SDM.Rmd
This script implements a Bayesian spatiotemporal species distribution model based on the INLA framework.
A rolling-window approach is used to generate estimated distribution maps for Mormon cricket across the study region.

3. Interactive Visualization

File: MC.html
An interactive web interface for exploring the estimated Mormon cricket distribution maps from 2002–2020 across Wyoming (WY), Nevada (NV), and Idaho (ID).

4. Data Release

The Releases section includes the environmental covariate raster data.

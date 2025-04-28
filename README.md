# Substrate Analysis of California MPAs

### Author: Michelle Yiv

Analyzing substrate types and distribution in California MPAs as part of the Bren School of Environmental Science and Management Master of Data Science Program. This project will be completed by the MarineBioMaps team, consisting of Bailey Jørgensen, Madison Enda, and Michelle Yiv.

## Purpose

There is still a need for statewide geospatial and statistical analysis of the distribution of habitat types within MPAs.

This repository will show analysis integrating existing spatial habitat datasets to generate a substrate layer for defined habitat types as described by the Pacific Marine and Estuarine Fish Habitat Partnership. Analysis will be done at an individual MPA level, by bio-regions defined by the California Department of Fish and Wildlife, and statewide.

## Repository Organization

#### Folder and file descriptions

#### **bioregion_analysis:**

This folder contains quarto documents detailing data preparation and calculations for substrate percentage calculation by bioregion.

**pointlobos_substrate_analysis**:

This file contains a quarto document with specific substrate percentage calculations for the Point Lobos MPA.

**statewide_substrate_analysis**:

This file contains a quarto document detailing statewide analysis of substrate percentage calculations.

**saving_substrate_data**:

This quarto documents details how to load in and save PMEP substrate data as an .RDS file used for all calculations in this project.

## Repository Structure

```
substrate
│  └──README.md
|  └──bioregion_analysis
|     └──nccsr_substrate.qmd
|     └──scsr_substrate.qmd
|     └──ncsr_substrate.qmd
|     └──ccsr_substrate.qmd
│  └──pointlobos_substrate_analysis
|  └──statewide_substrate_analysis
|  └──saving_substrate_data
│
```

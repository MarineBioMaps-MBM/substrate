# Substrate Analysis of California MPAs

### Author: Michelle Yiv

#### Contributors: Bailey Jorgensen, Madison Enda, Cori Lopazanski, Samantha Stevenson-Karl

Analyzing substrate types and distribution in California MPAs as part of the Bren School of Environmental Science and Management Master of Data Science Program. This project will be completed by the MarineBioMaps team, consisting of Bailey Jørgensen, Madison Enda, and Michelle Yiv.

For the regional analysis, we utilized the 5 distinct regions defined by the California Department of Fish and Wildlife and the Marine Life Protection Act. They are defined as such:

-   **SCSR** = South Coast Study Region

-   **NCCSR** = North Central Coast Study Region

-   **CCSR** = Central Coast Study Region

-   **NCSR** = North Coast Study Region

-   **SFBSR** = San Francisco Bay Study Region

The Pacific Marine and Estuarine Partnership (PMEP) utilized the Coastal & Marine Ecological Classification Standard (CMECS) to define major substrate categories:

-   **Anthropogenic Substrate**
-   **Biogenic Substrate**
-   **Coarse Unconsolidated Substrate**
-   **Fine Unconsolidated Substrate**
-   **Rock Substrate**
-   **Unconsolidated Mineral Substrate**

## Purpose

There is still a need for statewide geospatial and statistical analysis of the distribution of habitat types within MPAs.

This repository will show analysis integrating existing spatial habitat datasets to generate a substrate layer for defined habitat types as described by the Pacific Marine and Estuarine Fish Habitat Partnership. Analysis will be done at an individual MPA level, by bio-regions defined by the California Department of Fish and Wildlife, and statewide.

## Data:

.rds files created in the rds_creation repository from this MarineBioMaps Github Organization were used to load in the PMEP data filtered to California. See those repositories to access these .rds files.

Shapefiles for CA MPA Boundaries were downloaded from the [California Department of Fish and Wildlife](https://data.ca.gov/dataset/california-marine-protected-areas-ds582).

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

**interaction:**

This quarto document shows finding areas of biotopes / kelp and substrate interactions.

**substrate_abundance_calculations:**

This quarto document shows finding the abundance of substrate in MPAs and along the coast for statewide and all study regions, with tornado plots.

## Repository Structure

    substrate
    │  └──README.md
    |  └──bioregion_analysis
    |     └──nccsr_substrate.qmd
    |     └──scsr_substrate.qmd
    |     └──ncsr_substrate.qmd
    |     └──ccsr_substrate.qmd
    │  └──pointlobos_substrate_analysis.qmd
    |  └──statewide_substrate_analysis.qmd
    |  └──saving_substrate_data.qmd
    |  └──interaction.qmd
    |  └──substrate_abundance_calculations.qmd

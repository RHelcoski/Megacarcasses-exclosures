# Megacarcasses-exclosures

R code and raw data for the paper **“Elephant megacarcasses create grazing hotspots in African savannas.”** The repository contains the data and analysis workflow used to quantify grass productivity, grazing intensity, and dung deposition at elephant megacarcass sites in Kruger National Park, South Africa. :contentReference[oaicite:0]{index=0}

## Repository contents

- `code_exclosures_publish.qmd` — main Quarto analysis script for the manuscript
- `exclosureplantbiomass_all.csv` — herbaceous biomass data from paired exclosure and grazed plots
- `dung_all_3.csv` — dung survey data
- `CarcassSampleSummary_Sep2025.csv` — carcass site summary data
- `exclosure_locations_to_map.csv` — exclosure site locations used for mapping
- `basalt_granite.shp` — geology shapefile for Kruger National Park mapping :contentReference[oaicite:1]{index=1}

## Study summary

Elephant megacarcasses represent large, localized nutrient inputs in savanna ecosystems. This project tests whether those nutrient hotspots increase grass production, attract grazers, and alter dung deposition patterns around carcass sites. Analyses focus on:

- grass net aboveground primary productivity in exclosures
- grazing offtake in adjacent paired grazed plots
- elephant and ungulate dung density at carcass and matrix sites
- carcass-centered dung deposition gradients through space and time

## Reproducing the analyses

The manuscript analyses are run from `code_exclosures_publish.qmd`. The workflow assumes the repository files are stored together in a single working directory.

### Main R packages used

- `tidyverse`
- `sf`
- `ggplot2`
- `emmeans`
- `glmmTMB`
- `lme4`
- `patchwork`
- `ggspatial`

Depending on your local setup, additional packages may be required for mapping or model output.

## Data notes

- Exclosure analyses use paired exclosure and grazed control plots at multiple distances from elephant carcass centers.
- Dung analyses include both carcass sites and paired matrix sites.
- Geology data are used to map basaltic and granitic substrates across Kruger National Park.

## Status

This repository accompanies a manuscript currently in preparation/submission:

**Helcoski, R., Mkansi, N., Reed, C. G., Thompson, D. I., Burkepile, D. E., Lemoine, N. P., Hammill, E., and du Toit, J. T.**  
*Elephant megacarcasses create grazing hotspots in African savannas.*

## Contact

**Ryan Helcoski**  
Utah State University  
ryan.helcoski@usu.edu

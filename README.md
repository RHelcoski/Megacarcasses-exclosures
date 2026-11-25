# Megacarcasses-exclosures

R code and raw data for the paper **“Elephant megacarcasses leave legacies of grazing hotspots in patches of increased plant productivity in African savannas.”** The repository contains the data and analysis workflow used to quantify grass productivity, grazing intensity, and dung deposition at elephant megacarcass sites in Kruger National Park, South Africa. :contentReference[oaicite:0]{index=0}

## Repository contents

- `code_exclosures_Ecology_11_26.qmd` — main Quarto analysis script for the manuscript
- `exclosure_df.csv` — herbaceous biomass data from paired exclosure and grazed plots
- `dung_df.csv` — dung survey data

## Study summary

Elephant megacarcasses represent large, localized nutrient inputs in savanna ecosystems. This project tests whether those nutrient hotspots increase grass production, attract grazers, and alter dung deposition patterns around carcass sites. Analyses focus on:

- grass net aboveground primary productivity in exclosures
- grazing offtake in adjacent paired grazed plots
- elephant and ungulate dung density at carcass and matrix sites
- carcass-centered dung deposition gradients through space and time

## Reproducing the analyses

The manuscript analyses are run from `code_exclosures_Ecology_11_26.qmd`. The workflow assumes the repository files are stored together in a single working directory.

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


## Contact

**Ryan Helcoski**  
Utah State University  
ryan.helcoski@usu.edu

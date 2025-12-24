# diatom-epoch-shifts-sst-pca-logistic
Quarto analysis of diatom community shifts across the Pleistocene-Holocene transition, linking relative abundances to SST and summarizing structure with PCA and a supervised logistic separation direction.

# Diatom Community Climate Transition (Quarto)

This repository contains a reproducible Quarto analysis exploring how diatom community composition changes through time across the late Pleistocene to early Holocene transition using a Gulf of California sediment core dataset.

The workflow:
- Cleans diatom count data and converts counts to relative abundance
- Visualizes taxon trajectories through time
- Aligns diatom samples with reconstructed sea surface temperature (SST) using LOESS interpolation
- Compares distributions of key taxa across epochs (before vs after 11.7 kyr BP)
- Summarizes multivariate community structure using PCA
- Computes a supervised separation direction using logistic regression (with diagnostics for near-perfect separation)

R packages used:
- tidyverse
- patchwork
- ggridges
- corrplot
- colorspace
- hexbin
- RColorBrewer

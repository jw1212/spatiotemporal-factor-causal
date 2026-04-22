# spatiotemporal-factor-causal

This repository provides replication code for the paper  
**A Latent Factor Panel Approach to Spatiotemporal Causal Inference**.

- Paper: [arXiv preprint](https://arxiv.org/pdf/2509.10974)
- Code: [github.com/jw1212/spatiotemporal-factor-causal](https://github.com/jw1212/spatiotemporal-factor-causal)

## Overview

The repository includes code for the proposed methodology, simulation studies, and empirical analyses in the paper. It is intended primarily for replication and research use, rather than as a polished software package.

## Running The Code

The analysis scripts are Quarto documents. From the repository root, install the required R packages listed in the scripts, then render the relevant file. For example:

```sh
quarto render shared_confounding_simulation.qmd
quarto render birthweight_application.qmd
quarto render birthweight_adjustment_sets.qmd
```

The simulation scripts save replication outputs under `data/`. Some scripts also write rendered figures locally; these can be regenerated from the corresponding `.qmd` files.

## Citation

If you use this code, please cite the accompanying paper.

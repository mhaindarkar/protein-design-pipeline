# Protein Engineering Roadmap

A step-by-step protein engineering and protein bioinformatics portfolio project that starts from structural biology foundations and evolves into a modular AI-assisted protein design platform.

## Long-term vision

This repository is being built progressively from level zero to advanced versions, including:

- structure-based protein design
- constrained engineering workflows
- candidate evaluation and scoring
- protein language models
- generative protein design
- platform-style modularization

## First target

- Protein: Hen egg-white lysozyme
- PDB: 1LYZ

## Repository structure

- `data/` → raw and processed inputs
- `scripts/` → reusable Python scripts
- `notebooks/` → exploratory and teaching notebooks
- `results/` → generated outputs
- `figures/` → plots and visual summaries
- `configs/` → parameters and settings
- `docs/` → version history and project decisions


## Environment setup

```bash
conda create -n protein-roadmap python=3.11 -y
conda activate protein-roadmap
conda install -y jupyterlab pandas matplotlib numpy
pip install biopython
conda env export --no-builds > environment.yml

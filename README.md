# Supporting information to article 2024_MAHE_IL_pitfalls

This repository contains all data and supporting material for the article LINK TO ZENODO by M. Heubach ***et al.***.

Data:

* `data/figures` contains CSV of the curves shown in the individual figures found in the main manuscript as well as the SI.
* `data/xps_raw` contains CSV of all measured XP spectra.

Additional material:

* `doc/SI_database_interaction.ipynb` illustrates the usage of external databases to compare cyclic voltammograms from different sources.
* `doc/XPS.ipynb` provides additional information on the measured XP spectra (including data not shown in the manuscript or the supporting information).

## Installation

This project can be downloaded directly from the repository website or via

```sh .noeval
pip clone REPO NAME
```

To explore the Jupyter notebooks in `doc` interactively, install the required dependencies with conda (or mamba)

```sh .noeval
cd REPO NAME
conda env create -f environment.yml
conda activate REPO NAME
```

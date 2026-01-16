[![DOI](https://zenodo.org/badge/836711448.svg)](https://zenodo.org/doi/10.5281/zenodo.13166647)

# Supporting information to article MAHE_2024_IL_pitfalls

This repository contains all data and supporting material for the article
"Reproducibility of electrochemical measurements with ionic liquids: Is the water content the decisive parameter?" by
[M. Heubach ***et al.***](https://chemrxiv.org/engage/chemrxiv/article-details/6635102c21291e5d1d5c7a2d)

Data:

* [`./data/figures`](./data/figures) contains CSV of the curves shown in the individual figures found in the main manuscript as well as the SI.
* [`data/xps_raw`](data/xps_raw) contains CSV of all measured XP spectra.

[Read more](./data/README.md).

Additional material:

* [`./doc/SI_database_interaction.ipynb`](./doc/SI_database_interaction.ipynb) illustrates the usage of external databases to compare cyclic voltammograms from different sources.
* [`./doc/XPS.ipynb`](./doc/XPS.ipynb) provides additional information on the measured XP spectra (including data not shown in the manuscript or the supporting information).

## Installation

This project can be downloaded directly from the repository website or via

```sh .noeval
git clone git@github.com:theoechem/article_MAHE_2024_IL_pitfalls.git
```

Install [pixi](https://pixi.prefix.dev/dev/installation/) and install the dependencies via pixi.

```sh .noeval
pixi install
```

To explore the Jupyter notebooks in `doc` interactively use your favorite IDE or start jupyter via:

```sh .noeval
pixi run jupyter lab
```

# License

The contents of this repository are licensed under the [GNU General Public
License v3.0](./LICENSE) or, at your option, any later version.

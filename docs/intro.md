# Welcome to HPC Helper 2

[![License](https://img.shields.io/badge/License-AGPL_v3-red.svg)](https://github.com/praksharma/DeepINN/blob/main/LICENSE)  [![Jupyter Book Badge](https://jupyterbook.org/badge.svg)](https://praksharma.github.io/HPC-Helper-2/intro.html)

A continuation of HPC Helper, now documenting ARCHER2, CSD3, and Cumulus. This repository builds upon the original [HPC Helper](https://sunbird.readthedocs.io/), which was written for [Sunbird](https://portal.supercomputing.wales/index.php/about-sunbird/). 

* [ARCHER2](https://www.archer2.ac.uk/) – The UK's national supercomputing service.
* [CSD3](https://docs.hpc.cam.ac.uk/hpc/) – The Cambridge uni HPC cluster.
* [Cumulus](https://ukaeauk.sharepoint.com/sites/Cumulus/SitePages/Cumulus-2.aspx) – hosted at the MDC data centre at the UKAEA.
* [Friea](http://w3.freia.hpc.l/faq.html) - Very old, not used anymore. Hosted at UKAEA.

This docs is written on top of Jupyter book.

## Packages to install

* `ghp-import`
* `jupyter-book`

## Build the docs

```sh
jupyter-book build docs/
```

## Force build the docs

```sh
jupyter-book build --all docs/
```
# Push to github

```sh
ghp-import -n -p -f docs/_build/html
```
<!---
```{tableofcontents}
```
-->


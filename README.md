# VIP extras

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/r4lv/VIP_extras/patch-binder?filepath=binder%2Fwelcome.ipynb)

> additional material for [VIP](https://github.com/vortex-exoplanet/VIP)


## [Tutorials](./tutorials)

Tutorials in form of Jupyter notebooks can be found in the `tutorials/` folder. They can be visualized directly here on GitHub (by just clicking on them), or using the nbviewer service.

### 01. Main Tutorial

> [GitHub](./tutorials/01_adi_pre-postproc_fluxpos_ccs.ipynb) / [nbviewer](http://nbviewer.jupyter.org/github/carlgogo/VIP_extras/blob/master/tutorials/01_adi_pre-postproc_fluxpos_ccs.ipynb) / [binder](https://mybinder.org/v2/gh/r4lv/VIP_extras/patch-binder?filepath=tutorials%2F01_adi_pre-postproc_fluxpos_ccs.ipynb)

This tutorial covers most of the things VIP can do, especially:

- loading datasets
- pre-processing
- post-processing with ADI algorithms (Median subtraction, PCA, LLSG, ...)
- fake planet injection
- flux estimation (NEGFC) 
- contrast curves, S/N maps


### 02. Using HCIDataset objects

> [GitHub](./tutorials/02_hcidataset.ipynb) / [nbviewer](http://nbviewer.jupyter.org/github/carlgogo/VIP_extras/blob/master/tutorials/02_hcidataset.ipynb) / [binder](https://mybinder.org/v2/gh/r4lv/VIP_extras/patch-binder?filepath=tutorials%2F02_hcidataset.ipynb)

This tutorial shows how VIP's `HCIDataset` can be used for simple object-oriented access to all dataset related operations. It covers:

- loading/saving datasets
- simple operations (plotting, pre-processing, injecting)




## [Datasets](./datasets)

The datasets in the `datasets/` folder are available in FITS format, and VIP's own HCIDataset format (as `.npz`).

### NACO betapic

Small ADI cube with 39 frames. `naco_betapic.npz` contains just the "raw" data (`cube`, `psf`, `angles`, `px_scale`), while `naco_betapic_preproc.npz` is slightly preprocessed (cropped, psf normalized).

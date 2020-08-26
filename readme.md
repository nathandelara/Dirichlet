## Experiments for paper 8811

This folder contains 3 Jupyter notebooks to reproduce the experiments of paper 8811.

Required dependencies are listed in the *requirements.txt* file.
They are all available on PyPi.

We provide indicative running times for our setup:
* CPU:  Intel i7-7820HQ (2.90GHz)
* RAM: 16G


### main.ipynb

This notebook contains all experiments described in the paper except for those involving the **Wikilinks** and the **SNAP** datasets.

Just use the "Run all cells" command to reproduce the results.

**Indicative running time:** 6 minutes.

### wikilinks.ipynb

This notebook contains the experiments involving the **Wikilinks** dataset.

As this dataset is much bigger than the ones of **main.ipynb**, make sure that you have enough RAM available.

Just use the "Run all cells" command to reproduce the results.

**Indicative running time:** 27 minutes.


### snap_datasets.ipynb

This notebook contains the experiments on the social datasets.

First, download the files from the provided url.

Then, just use the "Run all cells" command to reproduce the results.

**Indicative running time:** 1 minute.
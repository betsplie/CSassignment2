# CSassignment2
Complex Systems assignment 2

## Project description
This repository contains the replication code for the early‑warning indicator results from Scheffer et al. (2009). We reproduce the six different plots in figure 1 of the origignal paper, showing the changing landscape, the rise in variance and the increased LAG(1) autocorrelation.

## Required packages
- numpy
- matplotlib
- scipy
- ipywidgets

The code also loads a shared POLDER matplotlib style file located at `templates/polder.mplstyle`.


## Parameter values used in our replication
| *Parameter* | *Meaning* | *Value* | *From paper* |
| --- | --- | --- | --- |
| K | Carrying capacity | 10 | yes |
| c_high | Maximum harvest rate (high resilience) | 1.0 | yes |
| c_low | Maximum harvest rate (low resilience) | 2.6 | yes |
| T | Number of time steps | 100,000 | no |
| dt | Time step | 0.01 | no |
| X_high | Initial condition for c = 1 | 8.8891 | no |
| X_low | Initial condition for c = 2.6 | 5.00 | no |
| noise | Noise amplitude | 0.02 | no |
| seed | RNG seed | 40 | no |

## Citation
Scheffer, M., Bascompte, J., Brock, W. A., Brovkin, V., Carpenter, S. R., Dakos, V., Held, H., 
van Nes, E. H., Rietkerk, M., & Sugihara, G. (2009). Early-warning signals for critical transitions. 
Nature, 461(7260), 53–59. https://doi.org/10.1038/nature08227
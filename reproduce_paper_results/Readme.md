Readme
================

This folder contains the files to replicate the simulations and real-world experiments of Gnecco et al. (2019 <https://arxiv.org/abs/1908.05097>).

A brief introduction to the `causalXtreme` package can be found at \[<https://nicolagnecco.github.io/causalXtreme>\].

The required R packages are: `causalXtreme`, `tidyverse`, `doParallel`, `doRNG`, `rngtools`, `tictoc`, `latex2exp`, `tools`, `mthemer` (installable from \[<https://rdrr.io/github/cszang/mthemer/man/mthemer.html>\]), and `kableExtra`.

This folder contains the following files:

-   `main.R`, which runs all simulations found in the paper, and produces all the plots and results
-   `simulation_0.R`, ..., `simulation_3.R`, which reproduce results of Section 5.1
-   `simulation_functions.R`, which contains all the helper functions for results of Section 5.1
-   `produce_charts.R`, which reproduces all figures of Section 5.1
-   `financial_data.R`, which reproduces all results and figures of Section 5.2
-   `river_map.R`, which reproduces the river map of Section 5.3
-   `river_data.R`, which reproduces all remaining results and figures of Section 5.3

It also contains the following folders:

-   `data`, which contains the raw data for the financial and river data experiments
-   `original_output`, which contains the output of simulations of Section 5.1. These simulations can be reproduced using `main.R`, but they are computationally intensive
-   `output`, which is an empty folder that contains all the results produced by `main.R`

### References

Gnecco, Nicola, Nicolai Meinshausen, Jonas Peters, and Sebastian Engelke. 2019. “Causal Discovery in Heavy-Tailed Models.” *arXiv Preprint arXiv:1908.05097*.
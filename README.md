# comparative

## Comparative Transcriptomics with R

Comparative transcriptomics studies enable to investigate the conservation and variability of gene
expression levels between tissues or biological processes of related species. This package aims to
provide users with easy to use methods as well as an visualization framework to perform comparative
transcriptomics studies with R.

## Tutorials

These tutorials will get you started with this package:

-
-
-

## Installation

### On Unix Based Systems

Now you can use the [devtools](http://cran.r-project.org/web/packages/devtools/index.html) package to install orthologr from GitHub.

```r
# install.packages("devtools")

# install the current version of comparative on your system
library(devtools)
install_github("HajkD/comparative", build_vignettes = TRUE, dependencies = TRUE)

```

### On Windows Systems

```r
# On Windows, this won't work - see ?build_github_devtools
install_github("HajkD/comparative", build_vignettes = TRUE, dependencies = TRUE)

# When working with Windows, first you need to install the
# R package: rtools -> install.packages("rtools")

# Afterwards you can install devtools -> install.packages("devtools")
# and then you can run:

devtools::install_github("HajkD/comparative", build_vignettes = TRUE, dependencies = TRUE)

# and then call it from the library
library("comparative", lib.loc = "C:/Program Files/R/R-3.1.1/library")
```

### Troubleshooting on Windows Machines

- Install `comparative` on a Win 8 laptop: [solution](https://github.com/HajkD/orthologr/issues/1) ( Thanks to Andres Romanowski )




<!-- README.md is generated from README.Rmd. Please edit that file -->

# tidymrp

<!-- badges: start -->

[![R-CMD-check](https://github.com/joekroese/tidymrp/workflows/R-CMD-check/badge.svg)](https://github.com/joekroese/tidymrp/actions)
<!-- badges: end -->

tidymrp makes it easy to run multilevel regression and
poststratification (MRP) analyses in R. It fits neatly into the
tidyverse and can be used with a range of modelling packages from
frequentist to Bayesian.

The focus of the package is on providing functions useful for MRP
workflows including creating poststratification frames, poststratifying
and visualising MRP results.

## Getting Started

### Installation

Install the latest development version from GitHub:

``` r
if (!require("devtools")) {
  install.packages("devtools")
}
devtools::install_github("joekroese/tidymrp")
```

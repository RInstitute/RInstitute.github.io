# Our FOSS activities

## R packages

* [dqmagic](dqmagic): Interface to libmagic
* [dqrng](dqrng): Fast random number generators
* [RcppArrayFire](rcpparrayfire): Interface to ArrayFire


At the moment these packages are not on CRAN, but you can install the current version via [drat](https://cran.r-project.org/package=drat):

``` r
if (!requireNamespace("drat", quietly = TRUE)) install.packages("drat")
drat::addRepo("daqana")
install.packages("dqmagic")
install.packages("dqrng")
install.packages("RcppArrayFire")
```

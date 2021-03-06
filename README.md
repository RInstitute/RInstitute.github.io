# Our FOSS activities

## R packages

* [dqmagic](dqmagic): Interface to libmagic
* [dqrng](dqrng): Fast random number generators
* [dqsample](dqsample): Bias-free alternative to R's 'sample' function
* [dqshiny](dqshiny): Enhance Shiny Apps with Customizable Modules
* [RcppArrayFire](rcpparrayfire): Interface to ArrayFire
* [tikzDevice](tikzDevice): R graphics device for LaTeX-friendly plots


At the moment `dqrng`, `dqshiny` and `tikzDevice` can be installed via CRAN. 
You can use our [drat](https://cran.r-project.org/package=drat) repository to install current versions of all packages:

``` r
if (!requireNamespace("drat", quietly = TRUE))
  install.packages("drat")
drat::addRepo("daqana")
install.packages("dqmagic")
install.packages("dqrng")
install.packages("dqsample")
install.packages("RcppArrayFire")
install.packages("tikzDevice")
```

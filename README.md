
<!-- README.md is generated from README.Rmd. Please edit that file -->

# rtichoke

<!-- badges: start -->

[![R-CMD-check](https://github.com/uriahf/rtichoke/workflows/R-CMD-check/badge.svg)](https://github.com/uriahf/rtichoke/actions)
[![CRAN
status](https://www.r-pkg.org/badges/version/rtichoke)](https://CRAN.R-project.org/package=rtichoke)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![Codecov test
coverage](https://codecov.io/gh/uriahf/rtichoke/branch/main/graph/badge.svg)](https://codecov.io/gh/uriahf/rtichoke?branch=main)
<!-- badges: end -->

The goal of rtichoke is to …

## Installation

<!-- You can install the released version of rtichoke from [CRAN](https://CRAN.R-project.org) with: -->
<!-- ``` r -->
<!-- install.packages("rtichoke") -->
<!-- ``` -->

You can install the development version from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("uriahf/rtichoke")
```

## Example

This is a basic example which shows you how to solve a common problem:

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this. You could also
use GitHub Actions to re-render `README.Rmd` every time you push. An
example workflow can be found here:
<https://github.com/r-lib/actions/tree/master/examples>.

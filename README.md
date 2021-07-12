
# ch

<!-- badges: start -->
[![CRAN status](https://www.r-pkg.org/badges/version/ch)](https://CRAN.R-project.org/package=ch)
[![R-CMD-check](https://github.com/passing/workflows/R-CMD-check/badge.svg)](https://github.com/passing/actions)
<!-- badges: end -->

The goal of ch is to solve some questions.

## Installation

You can install  ch :

``` r
install.packages('ch')
# or from github
devtools::install_github('tsiamut/ch')
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(ch)
#basic example code
# You can draw a ruler:
draw_ruler(5)
## And even draw  the periodic table.
period_table()
show_color(colors())
sym2poly('x*4 + x^4 + 5*x^7 + x*x^9')
```




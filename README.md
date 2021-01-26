
<!-- README.md is generated from README.Rmd. Please edit that file -->

# toypackage

<!-- badges: start -->

<!-- badges: end -->

The goal of toypackage is to provide an example of how to build a
bare-bones R package.

## Installation

You can install the development version from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("prestevez/toypackage")
```

## Example

This is a basic example of the functions in the package.

``` r
library(toypackage)
## basic example code

hello("Alice")
#> [1] "Hello Alice!"
greetings(c("Alice", "Bob"))
#> [1] "Greetings Alice." "Greetings Bob."
```

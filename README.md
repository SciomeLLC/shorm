# shorm

<!-- badges: start -->
<!-- badges: end -->

# Overview

The shorm package provides functions for hormesis screening by classifying the shapes of dose-response curves based on semiparametric tests. The shapes are indications of different potential toxicology effect. It also offers a scalable visualization scheme to present testing conclusions for large-scale dataset with a large number of dose-response curves.

# Installation

You can install the development version of shorm from GitHub with:

``` r
# install.packages("devtools")
devtools::install_github("YinglJin-0203/WhatShape")
```

# Usage and Examples

## Generate a Data Set

``` r
x <- seq(0, 1, length.out = 48)
y <- 2*sqrt(x)+rnorm(48)
y[17:32] <- y[17:32]+0.5
y[33:48] <- y[33:48]+1
curve <- data.frame(x, y)
curve$rep <- rep(1:3, each = 16)
```

## Single SHARP Test

### Fixed-model based test

``` r
sharpt <- SHARPtest(curve, xName = "x", yName = "y")
```

### Mixed-model based test

``` r
sharptm <- SHARPtest(curve, mixed = TRUE, xName = "x", yName = "y", rName = "rep")
```

## Repeated SHARP Test

### Fixed-model based test

``` r
rsharpt <- RepeatSHARP(curve, nRep = 10, xName = "x", yName = "y")
```

### Mixed-model based test

``` r
rsharptm <- RepeatSHARP(curve, nRep = 10, mixed = TRUE, xName = "x", yName = "y", rName = "rep")
```

## Visualize Results
``` r
SharpScatter(sharpt[1], sharpt[2], sharpt[3], sharpt[4])
```

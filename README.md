
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Rgis: streamlining GIS operations in R

<!-- badges: start -->

[![Travis-CI Build
Status](https://travis-ci.org/Pakillo/rgis.svg?branch=master)](https://travis-ci.org/Pakillo/rgis)
[![Codecov test
coverage](https://codecov.io/gh/Pakillo/rgis/branch/master/graph/badge.svg)](https://codecov.io/gh/Pakillo/rgis?branch=master)
[![HitCount](http://hits.dwyl.com/Pakillo/rgis.svg)](http://hits.dwyl.com/Pakillo/rgis)
<!-- badges: end -->

<https://pakillo.github.io/rgis>

<br>

<img src="logo.jpg" width="100%" />

## Installation

This package depends on package
[`velox`](https://github.com/hunzikp/velox), which has been removed from
CRAN as of 2020-03-17 (see
[here](https://github.com/hunzikp/velox/issues/43) for more info). While
it (hopefully) comes back to CRAN, you will need to install `velox`
**before** attempting to install `rgis`, like this (thanks @lbusett for
the tip):

``` r
devtools::install_version("velox", version = "0.2.0")
```

Then you can install `rgis`:

``` r
devtools::install_github("Pakillo/rgis")
```

## Current functions:

  - `ungzip`: Decompress gzip files.

  - `fast_extract`: Fast extraction of raster values for points and
    polygons.

  - `fast_mask`: Fast masking of raster values based on another raster
    or polygon layer.

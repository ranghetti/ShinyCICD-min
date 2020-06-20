
# ShinyCICD

<!-- badges: start -->
[![R build status](https://github.com/ranghetti/ShinyCICD-min/workflows/CI-CD/badge.svg)](https://github.com/ranghetti/ShinyCICD-min/actions)
<!-- badges: end -->

The goal of ShinyCICD is to provide a simple example of packaged Shiny app to showcase CI/CD pipelines.

## Installation

You can install ShinyCICD from GitHub with

``` r
remotes::install_github("miraisolutions/ShinyCICD-min")
```

The corresponding Shiny app can be then served launched by simply calling the `run_app()` exported function:

``` r
ShinyCICD::run_app()
```

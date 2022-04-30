# Homework 08: Collecting and analyzing data from the web

This assignment aimed to help us learn the process of accessing data using API and web scraping. See detailed instructions for this homework assignment [here](https://cfss.uchicago.edu/homework/webdata/). The data files used for this assignment were from the `gapminder` and `geonames` packages and [USGS website](https://earthquake.usgs.gov/fdsnws/event/1/#format-geojson). 

Helpful links for reference: 
[creating world maps](https://datavizpyr.com/how-to-make-world-map-with-ggplot2-in-r/) and [finding color names](https://www.r-graph-gallery.com/ggplot2-color.html)

## Required packages

The following packages were used:

```r
library(tidyverse)
library(gapminder)
library(geonames)
library(countrycode)
library(httr)
```

## Files included

The following files were included in this repository:

* [gapminder.Rmd](gapminder.Rmd) - analysis of the `gapminder` and `geonames` data
* [earthquake.Rmd](earthquake.Rmd) - analysis of the earthquake data
* [gapminder.md](gapminder.md) - output of `gapminder` analysis
* [earthquake.md](earthquake.md) - output of earthquake data analysis

Report on Gun Murders
================
ZiCheng OU
2/3/2020

## Introduction

This is a report on 2010 gun murder rates obtained from FBI reports. The
original data was obtained from [this Wikipedia
page](https://en.wikipedia.org/wiki/Murder_in_the_United_States_by_state)

We are going to use the following library:

``` r
library(tidyverse)
```

    ## Warning: package 'ggplot2' was built under R version 3.6.2

    ## Warning: package 'dplyr' was built under R version 3.6.2

and load the data we already wrangled:

``` r
load("rda/murders.rda")
```

## Murder rate by state

We note the large state to state variability by generating a barplot
showing the murder rate by state:

![](Report-on-Gun-Murders_files/figure-gfm/murder-rate-by-state-1.png)<!-- -->

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](Report-on-Gun-Murders_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
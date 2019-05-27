
inomaly: my first package (On developing..)
=====================================================================================================

*solution for big data*

`inomaly` is an R package which contains:

R function for filling in missing values of a variable from one data frame with the values from another variable.

Installation
------------

``` r
# install.packages("devtools")
devtools::install_github("irwannafly/inomaly")
```

Example
=====================================================================================================
``` r
# Create data set with missing values
#' naDF <- data.frame(a = sample(c(1,2), 100, rep=TRUE), 
#'                    b = sample(c(3,4), 100, rep=TRUE), 
#'                    fNA = sample(c(100, 200, 300, 400, NA), 100, rep=TRUE))
#'
#' # Created full data set
#' fillDF <- data.frame(a = c(1,2,1,2), 
#'                      b = c(3,3,4,4),
#'                      fFull = c(100, 200, 300, 400))
#'
#' # Fill in missing f's from naDF with values from fillDF
#' FilledInData <- FillIn(naDF, fillDF, Var1 = "fNA", Var2 = "fFull", KeyVar = c("a", "b"))
```

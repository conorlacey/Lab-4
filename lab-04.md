Lab 04 - La Quinta is Spanish for next to Denny’s, Pt. 1
================
Conor Lacey
02-04-2023

### Load packages and data

``` r
suppressWarnings(library(tidyverse))
library(dsbox) 
```

``` r
states <- read_csv("data/states.csv")
```

### Exercise 1

``` r
dn<-dennys
nrow(dn)
```

    ## [1] 1643

``` r
ncol(dn)
```

    ## [1] 6

In the dennys dataset, there are 1,643 row and 6 columns. Each row
represents an individual dennys location. The variables in this data set
include…

``` r
colnames(dn)
```

    ## [1] "address"   "city"      "state"     "zip"       "longitude" "latitude"

Now let’s look at the La Quinta dataset.

``` r
lq<-laquinta
nrow(lq)
```

    ## [1] 909

``` r
ncol(lq)
```

    ## [1] 6

The La Quinta dataset has 909 rows and 6 columns. Each row represents
one La Quinta location. The variables in the dataset are as follows:

``` r
colnames(lq)
```

    ## [1] "address"   "city"      "state"     "zip"       "longitude" "latitude"

### Exercise 2

Remove this text, and add your answer for Exercise 2 here. Add code
chunks as needed. Don’t forget to label your code chunk. Do not use
spaces in code chunk labels.

### Exercise 3

…

### Exercise 4

…

### Exercise 5

…

### Exercise 6

…

Add exercise headings as needed.

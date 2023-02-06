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

### Exercise 2

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

### Exercise 3

Going to the La Quinta website there are La Quinta’s outside the U.S.
that include Canada, Mexico, China, New Zealand, Turkey, United Arab
Emirates, Chile, and Columbia.

Going to the Denny’s website it was actually difficult to find
information on locations outside the U.S. Fortunately, statista.com
provides data on this if you follow this link:
<https://www.statista.com/statistics/947495/number-of-dennys-restaurants/>

From this link we find that there are Denny’s outside the U.S. that
include Canada, Puerto Rico, Mexico, Phiippines, New Zealand, Honduras,
United Arab Emirates, Guatemala, Costa Ric, Guam, Indonesia, El
Salvador, United Kingdom, Aruba, Curacao N.V., and the Domincan
Republic.

### Exercise 4

I think one way to determine if a location is outside the U.S. for both
datasets is to see if the state abbreviations matches up with any of the
abbreviations in the state dataset. If it does not, then it must be
outside the U.S.

### Exercise 5

### Exercise 6

…

Add exercise headings as needed.


# The EC4023 package

EC4023 contains tutorials for data analysis and quantitative methods at the University of Limerick.

### Installation

Install the package from GitHub via devtools together with learnr using the following commands.

``` r
install.packages("devtools")
install.packages("learnr")

devtools::install_github("lkuld/EC4023")
```

### Examples


``` r
library(EC4023)
library(learnr)

## to see all available tutorials
available_tutorials("EC4023")

## to start the first tutorial "Tutorial_1_Introduction"
run_tutorials("Tutorial_1_Introduction", "EC4023")
```


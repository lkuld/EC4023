
# The quantsUL package

quantsUL contains tutorials for data analysis and quantitative methods at the University of Limerick.

### Installation

Install the package from GitHub via devtools together with learnr using the following commands.

``` r
install.packages("devtools")
install.packages("learnr")

devtools::install_github("lkuld/quantsUL")
```

### Examples


``` r
library(quantsUL)
library(learnr)

## to see all available tutorials
available_tutorials("quantsUL")

## to start the first tutorial "Tutorial_1_Introduction"
run_tutorials("Tutorial_1_Introduction", "quantsUL")
```


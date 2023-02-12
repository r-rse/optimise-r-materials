
# optimise-r-materials

<!-- badges: start -->
<!-- badges: end -->

This repository contains materials accompanying the R-RSE course on [**"Optimising R workflows"**](https://optimising-r.netlify.app).

## scripts

The root of the projects contains empty scripts, ready to work in during the workshop

## `data/`

The `data/` directory contains parquet files of data on synthetic UK populations of varying sizes generated using package [`synthpop`](https://www.synthpop.org.uk/):

- `data/synthpop_100000.parquet`: Contains data on 100,000 individuals.
- `data/synthpop_1000000.parquet`: Contains data on 1,000,000 individuals.
- `data/synthpop_10000000.parquet`: Contains data on 10,000,000 individuals.


### Data column contents

- sex     : chr  sex
- age     : int  age
- agegr   : chr  age group of individual
- socprof : chr  social/professional status 
- income  : int  income (£)
- marital : chr  marital status
- edu     : chr  education
- sport   : logi whether individual participates in sport
- smoke   : logi whether individual smokes
- nociga  : int  if smoker, number of cigarettes smoked per day. Otherwise `NA`
- alcabuse: logi whether individual abuses alcohol
- bmi     : num  body mass index
- location: chr city of residence

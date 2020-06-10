by Sandra Schwegmann


## Variable description 
* Describes the variables in the King Country House Price Data set and newly created ones

## Type of data and data conversions
* Quick look what's in the data
* Format changes (e.g. change date style, replace invalid signs)

## Missing data treatment
* Overview which data have missing data
* treatment of missing data

## Basic statistics
* Quick look through basic statistics (mean, min, max etc)
* create log of Price

## Correlation
* check correlation between all individual variables
  * correlogram
  * pairplot
  
## Histograms
* Have a look on the distribution of each variable

## Identify impact of individual variables on pricing - a closer look
* calculation of r^2
* check differences in r^2 between price and log(price)
* test impact on outlayer in Bedrooms
* test impact of many rooms vs less rooms on price
* test impact of the grade
* test impact of view
* test impact of conditions

## New Variables
* creation of new variables out of existing to test wether they can more accurately predict the price
* check maximum distance to the waterfront
* does living area to lot area ratio matter?
* is it important to have basement area?
* renovated recently or not - does it change anything?
* old houses vs new houses - is there a difference in pricing?

## Creating models to predict prices for certain conditions
* predict price using all original data
* predicting log Price using all original data
* predicting log Price only using original data with highest r^2
* predicting log Price using most important and important new variables


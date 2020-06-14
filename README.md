This project is centered around exploratory data 
analysis (EDA) techniques and statistical analysis, 
as well as modeling data using linear regression.
Goal is to generate a model for house price prediction. Setting: A customer would like to buy a house whose price is within +/-20% of the average house price. It should have good conditions, 2-4 bedrooms and a size of 650-1000 square feet. Water-view is not necessary but would be nice, as would be vicinity to waterfront instead of waterview. The question is how individual parameters would influence the price and what kind of combination would suit the price expectations of the customer best.   

## The Repository consists of:
* EDA-Project_House_Prices.pdf summarzing finding in presentation-style
* EDA-Project_House_Prices.ipynb Jupyter Notebook containing the code and steps of analysing data
* a figure showing the correlation between all of the initial variables

## Summary
- Most important influencer of price is the size of the house
- Also having a basement or not is important: Houses without basements are on average 135400 USD cheaper than houses with basement
- Waterfront objects are expensive: houses with waterfront view are an average twice as expensive as houses without. The price of houses without waterfront view decreases with distance to the water side.
- Houses renovated within the previous ~30 yrs are more expensive then houses without renovation or which has been renoved befor 1988. On average, a recently renovated house coast 127100 USD more than a non-renovated house.

## Outlook
* It still needs to be tested how good the model performance is.
* The model may require some improvements after testing.
* It still needs to be shown, which kind of objects fullfil the criteria price beeing within +/- 20% of mean house price.
* The impact that distance to water areas has on the price should be improved by using geographical positions of water areas. => Calculating the real distance of houses to waterfront instead of using distance to an waterview object as proxy.
* A longer time series can help to identify whether the season and how much the inflation rate has an impact on prices.
* Also the impact of rural vs. urban location could be investigated in further analysis.



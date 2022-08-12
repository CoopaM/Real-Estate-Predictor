# Real-Estate-Predictor
**Author:** Cooper McCombs

## Repository Contents
- [Data](https://github.com/CoopaM/Real-Estate-Predictor/tree/main/Data)
- [.gitignore](https://github.com/CoopaM/Real-Estate-Predictor/blob/main/.gitignore)
- [README.md](https://github.com/CoopaM/Real-Estate-Predictor/blob/main/README.md)
- [starter_notebook.ipynb](https://github.com/CoopaM/Real-Estate-Predictor/blob/main/starter_notebook.ipynb)
- [time.yml](https://github.com/CoopaM/Real-Estate-Predictor/blob/main/time.yml)

## Table of Contents
- [Overview](#overview)
- [Business Problem](#business-problem)
- [Data](#data)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [For More Information](#for-more-information)

## Overview
For my final project with flatiron, I wanted to find trends in zipcodes to predict the median prices of homes for each zipcode. This allows me to estimate where the housing market is right now and where it will be in a years time based on previous years.

## Business Problem
What I want to achieve in this project is to give an accurate estimation of the real estate market and where it's going. With this information, I would help upcoming investors and homeowners get a understanding of how they should invest their money.

## Data
I got my data from [Zillow](https://www.zillow.com/research/data/). It uses median housing prices from the years 2000 to 2022. The reason why the median value of homes is used instead of mean to resist outliers from effecting the data. The dataset I used consists of over 27000 rows of data points and takes information from the first of the month.


## Results
Most zipcodes indicate a positive trend in the current market. My model forcasts one year in advance and accounts for around 87% variance. The zipcode I decided to use for an example is 35173 or Trussville, Alabama and it estimates over a $48000 ROI(return of investment).
[](https://github.com/CoopaM/Real-Estate-Predictor/blob/main/graphs/Model.png)
This graph represents an example of my final model, but the function I wrote allows you to input any zipcode to output a forecasting graph. 

## Conclusion
In conclusion, the housing market right now is really good and keeps increasing in prices. This means now is the time to rent homes as you want to set the rate of homes when the value of the house is high in order to have a high rate of rent. This also means that you should not buy right now, but rather sell as I am estimating that in a year or two the housing market will top off and start going back down.

## Future Work
If I had more time to work on this project I would:
- Accommodate for the economy and housing market
- Scrape more housing data from different sources to get a more accurate representation of the whole market
- Increase the accuracy of my model
## For More Information
- [Zillow Website](https://www.zillow.com/research/data/)
 
## Repo Map
```
├── Data                                     
|   ├── Zip_zhvi_uc_sfrcondo_tier_0.33_0.67_sm_sa_month.csv  
|   └── zillow_data.csv
├── 
|   └── confusion.png
├── Notebooks  
|   └── Draft Notebook.ipynb
├── .gitignore 
├── FinalNotebook.ipynb 
├── README.md 
└── The Stars.pdf
```
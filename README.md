# What Beer to Brew

The US is home to over 6,000 breweries. Craft beer has grown in popularity significantly over the last ten years and with the increase in competition and growth in the craft beer drinking community, I have taken a deeper look into what beer drinkers are drinking and enjoying the most. Can a brewery use consumer data to produce a beer that will become popular amongst craft drinker? If so, how much insight can be incorporated into the production of the beer. 

The data used in this project is from beeradvocate.com. It includes 1.5 million individual reviews on over 66,000 beers, both domestic and international collected from a ten year timeframe. In the jupyter notebook, I perform some exploritory data analysis and feature engineering before modeling. I used both a random forest regressor and classifier to predict the overall rating of the beers in the sample set. Due to the size of the sample set, hypertuning of the parameters became too lengthy to complete, but the base model's accuracy, precision and recall has lead me to be confident in its results despite being unable to adjust the parameters.

I used aws, specifically s3 and sagemaker to complete this project. 


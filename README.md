# Canadian-Rent-model Project
This project was to find the best possible model in order to predict the price. This is the dataset that was used for this analysis. <br>
https://www.kaggle.com/datasets/sergiygavrylov/25000-canadian-rental-housing-market-june-2024es ,
### Goals: 
* find certain linearity or correlation between all features
* fix the data and get the best features
* find a model best suited for finding the price
### Description:
* imports
* data visualization
* filling null values
* finding best features and scaling
* Models: basic linear regression, polynomial, LassoCV and RidgeCV
### Analysis:
From the start, we saw that not many of the features correlated with each other, based on the heatmaps and the pairgrid scatterplots. When it came to creating the models, the rmse and the r2 scores were really low, which is often not a good sign. Most of the models had an rmse between 600$ and 800$, which in our case, an average of 600$ difference for rent prices, are big. My r2 score were around 50%, which means it couldn't really capture its variability of the data
### Changes in the future:
I would maybe change some of the variables and fix the encodings, to try to make them more accurate.

# DSCDatathon

A combination of 3 datasets was used to merge into a single, cleaned and more useful dataset using R (see DSCDatathon 2\merged.csv in the attached GitHub files)

## Links to the datasets used
Obesity dataset: https://apps.who.int/gho/data/node.main.A900A?lang=en <br />
CO2 emissions dataset: https://www.kaggle.com/kkhandekar/co2-emissions-1960-2018 <br />
GDP/capita dataset: https://www.kaggle.com/nitishabharathi/gdp-per-capita-all-countries <br />
**For the set-up, please scroll down to the bottom of this README.md file**

The rapid climate change and increasing obesity rates are two significant concerns for policy makers around the world. We aim to determine if climate change, in particular increasing CO2 emissions, be a driver for the global obesity rates. Additionally, we also looked at the GDP per capita for countries in order to determine if a relationship between that and obesity exists. At first it might seem like CO2, GDP/capita and obesity rates are completely unrelated. Therefore, we aim to uncover relevent trends and will then present our findings. 

## Data Analysis and Methodology 
For the purpose of this project, 3 primary data sets were used; global CO2 emissions per capita, prevalence of obesity among adults and the GDP per capita, with all values categorized based on countries. For purposes of data cleaning, processing and plotting, we decided to use R as a programming language since it was common in the team-members' skill-set.

We chose to take the regression route since we were more focussed on the gathering, cleaning and processing big-data rather than machine learning. In the future, however, we can employ machine learning models to provide an estimated value from predictive features with the same datasets. For instance, if policy makers were to implement caps on how much CO2 emissions a nation is allowed to produce annually. A machine-learning predictive model will be extremely useful in this case as it might give us predictions of limits on meat production and other industries (which will inturn curb the national CO2 emissions)

## Hypothesis
GDP/capita, CO2 emmissions/capita and prevelence of obesity, all have a positive relationship (ideally linear)

## Conclusion

The following observations and inferences were made:
1. The GDP per capita had a positive relationship with the obesity levels.
2. There was no significant relationship between the global CO2 levels on the other 2 atributes (prevalence of obesity worldwide, or the GDP, which contradicts our hypothesis). However, an article published by The National Library of Medicine (one of several) stated that "GDP positively related to CO(2) emissions with a recognised sustainable carbon footprint of less than 5 tonnes per capita occurring at a GDP of <$US15,000" (https://pubmed.ncbi.nlm.nih.gov/22305524/).

Based on our hypothesis (a rise in CO2 emissions was linked to increasing obesity levels), we assumed that increased meat consumption and production could be a key factor in the positive relation between CO2 and obesity. However, this was not the case since the CO2 emmissions per capita did not increase.

On the other hand, the prevalence of obesity showed a strong, almost linear relation, with the GDP/capita levels. 


## Challenges faced
The most significant challenge we faced was in terms of our CO2 emmissions per capita dataset. Contrary to what was expected, and contrary to what research articles show, our data showed no significant rise in the levels (it was infact a slight decline)


## Setting up the environment for reproducability
Our code is in the form of an RMarkdown File. In order to reproduce the code, all you really need is the .zip file with the 3 datasets we used and the .rmd file (uploaded onto GitHub).

You will, however, need to edit the root folder in the commands that import the datasets (or you can go into RStudio, navigate to File-> Import Dataset to import the 3 datasets and then you can ignore the following code block in the .rmd file)

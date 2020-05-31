# COVID_model
Stochastic SEIR modelling of people effected due to COVID-19.
The project is inspired by the idea to show the effect of restrictions in our civil rights towards the spread of the novel virus. To be a little more specific, we want to analyse - what happens to the overall spread rate of the virus when a certain section of the society takes all the governemnt recommended precautions in their area vs. when they don't.

As this is an ongoing project, we will be updating the details as per our research

Data file updation commands in R:
Link: https://kjhealy.github.io/covdata/
1. install.packages("covdata")
2. library(covdata)
3. update.packages("covdata")
4. write.csv(covdata::covnat,"covnat.csv")

New data source:
https://github.com/owid/covid-19-data/tree/master/public/data

# Exploring Which Predictors Are Most Relevant in Determining the Quality (xG) of a Chance

In this project, JP Borsos and Nicholas Aufiero explored how different predictors impacted chance creation, analyzing 15 years of FC Barcelona event data from StatsBomb. Our response was StatsBomb's xG (expected goals) value, which demonstrates the likelihood of a shot resulting in a goal, in other words the quality of the chance. Ultimately, our final model's predictors were the shot distance from goal, shot distance squared, the shot angle to goal, shot angle squared, and a binomial predictor denoting whether or not the shot was a header.

"RP 4.Rmd" shows the various different regression models we developed and their diagnostics. 

"Converting and Developing ShotInfo From Event Data.ipynb" shows the code we used to manipulate the StatsBomb event data and develop the predictors we wanted to analyze.

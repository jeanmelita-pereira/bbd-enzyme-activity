# bbd-enzyme-activity

## Objective
To model and analyse enzyme activity using rsm and compare linear and quadratic regression models
we want enzyme activity ,we know it depends on Temperature,ph,substrate conc,but we dont know which of them combinations give max enzyme activity we dont know.
IN real life need to do 3^3 = 27 experiments which becomes expensive
BBD says dont do all 27 experiments,instead do 15 carefully chosen experiments.


## Dataset
used fake experimental conditions for all the 3 factor inputs and fed activity(response) values to train the model

## Results
linear model performed well
i squared the linar values as in real life ,enzyme activity values first increase ,reach maximum and then decreasewhich made it quadratic
but quadratic values didnt perform well,there was a case of overfitting maybe due to lack of variety of data and combinations.

## Visualization
predicted vs actual plot was generated to evaluate model accuracy

## Tools used
Python,Pandas,Numpy,Matplot,Seaborn,pyDOE3

## conclusion
results show proper feature selection is important in RSM based modeling

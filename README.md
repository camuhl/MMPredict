# March Madness Predictions


##Introduction 

This is a personal project used to explore webscraping techniques by gathering data from basketball reference in order to fit a model to the data and predict the winners of the NCAA Men's national basketball championship (aka March Madness) tournoment games. Full project notebook available under MM.ipynb

## Packages used
BeautifulSoup
pandas
numpy
sklearn
pylab
fancyimpute
scipy

## Conclusions
While testing on historical data generated promising results, when comparing the model's expected results to actual results from the 2021 games the model was not very predictive.  This could be considered an outlier due to the impact COVID-19 had on the teams schedules i.e. not allowing the teams to play others outside of their respective conferences and thusly giving an abnormal and small sample of games. However, it does show the model could be improved by better accounting for teams' strength of schedual. Additionally, the model could have been further trimed as many of the columns the model was trained on contained replicated data.

# Classifying-Chicago-Car-Accidents
This README.md lists the project scenario, goals, methodology, and a summary of the files in the repository.

### Project File Summary
- <b>README.md</b> - a summary of all contents in this repository.
- <b>/Data</b> - The csv files downloaded for the cityofchicago data portal as well as the cleaned csv files used for modelling
- <b>/DataCleaning</b> - Jupyter Notebook containing all code used for the data cleaning steps
- <b>/EDA</b> - Jupyter Notebook containg all exploratory data anlysis and visualizations
- <b>/FeatEng</b> - Jupyter Notebook containing all code used for feature engineering
- <b>/Modeling</b> - Jupyter Notebook containing all code used for the logistic regression
- <b>/Presentation</b> - A pdf of the powerpoint presentation

### Project Scenario:
In 2017 the city of Chicago unveiled its Vision Zero plan to eliminate all traffic fatalities and serious injuries by 2026. This came following a jump in the number of deaths and serious injuries from traffic crashes by 8% between 2010-2014. One of the action steps of Vision Zero is the stricter enforcement of traffic laws, focusing on dangerous driving behaviors that cause most severe crashes. In Chicago, any accident that results in a fatality requires a mandatory investigation, but this creates a problem: Dangerous drivers are only investigated after a person is killed. How can dangerous drivers be identfied and taken off the street before someone is killed or seriously injured? To solve this problem the city of chicago has hired a freelance data scientist to create a model that identifies dangerous drivers after all accidents, including minor ones.

### Project Goals:
- To be able to predict, following a car accident, whether or not a dangerous driver was the cause.
- To fulfill this objective, a classification model will be built that identifies whether a car accident was caused by criminal driving behavior, or non-criminal driving behavior.

### Methodology 

   -  Download and clean data from cityofchicago data portal.
   -  Bin primary_contributory_cause column into binary class: 'Criminal Driving' / 'Non-Criminal Driving'.
   -  Feature engineer additional columns.
   -  Perform Exploratory Data Analysis (EDA)
   -  Split the data into a training set and test set.
   -  Fit a logistic regression model to the training set.
   -  Perform hyperparameter tuning using RandomSearchCV / GridSearchCV.
   -  Test the optimized training model on the test data and evaluate score.
   -  Create a presentation to translate findings into actionable insights for the Chicago Police Department.

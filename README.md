SiteEUI_Prediction


The task involves roughly 100k observations of building energy usage records collected over 7 years and a number of states within the United States. The dataset consists of building characteristics (e.g. floor area, facility type etc), weather data for the location of the building (e.g. annual average temperature, annual total precipitation etc) as well as the energy usage for the building and the given year, measured as Site Energy Usage Intensity (Site EUI). Each row in the data corresponds to the a single building observed in a given year. The task is to predict the Site EUI for each row, given the characteristics of the building and the weather data for the location of the building.

Target site_eui: 
Site Energy Usage Intensity is the amount of heat and electricity consumed by a building as reflected in utility bills

Implementation:-
• Used four regression techniques: Linear regression, decision tree, XGBoost, CatBoost 
• CatBoost gave r2 score of 85% after hyperparameter tuning.
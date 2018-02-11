CT Bike Crash Data

Using this data, I would like to attempt to predict the severity of a bike crash given a number of situational features - these include road condition, road type, weather condition, gender, age, helmet usage, high visibility clothing usage, light condition, and operator sobriety. I think this could be interesting to help cyclists understand what conditions can result in the most severe crashes and help them to avoid those dangerous situations. Accident severity is rated on a scale of 1-5, with 1 being no injury and 5 being a fatality.

The data in this set covers 19 years of crashes, from 1995 to 2014. Most of the data in the set is categorical, which will force the creation of a number of boolean dummy variables - in an attempt to cut down on these variables, I will consolidate some of the categories to increase clarity. For example - weather conditions "Rain", "Snow", "Hail", and "Sleet" are simply consolidated to "Precipitation."

Looking at the results of the tuned & unturned regression trees, the RSME does not indicate a great level of fit. Unfortunately, this may indicate that the given predictors are poor for identifying the severity of a bicycle crash.

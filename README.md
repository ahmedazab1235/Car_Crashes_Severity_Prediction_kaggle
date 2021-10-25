# Car Crashes' Severity Prediction

## Reaching 74.473 %



### File descriptions
* train.csv - the training set.
* holidays.xml - Information about whether the day is a regular day or a holiday.
* weather-sfcsv.csv - Information about the weather.
* test.csv - the test set.

### Data fields
* Lat - Latitude of the incident
* Lng - Longitude of the incident
* Bump, Crossing, Give_Way,Junction, NoExit, RailWay, Roundabout, Stop, Amenity, Side - The characteristics of the location where the incident has taken place, * * * several can be true at the same time. Side is the side of the street.
* State - the state from which this dataset is coming from
* Distance - the distance of the traffic jam provoked by an accident
* Timestamp - the moment when the incident has occurred.
* Severity - (Target) An indicator representing the severity of the car crash and possible impacts on the traffic. Values can range from 1 to 4, the highest value * translates a highest impact.
> Severity is the target variable for that exercise. The target variable is the one we want to predict thanks to the predictive system module already present that you will build during that Programming Challenge.







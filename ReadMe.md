Built a model that predicts flight delays specifically for Pittsburgh airport using data from Bureau of Transportation Statistics. To improve the accuracy of our model, added features to the data. For example :

1) Track the flights by the tail numbers that are arriving and have to depart soon.


2) check how many flights have taken off or landed 30 minutes before the scheduled departure time of a flight. The assumption is that if the number of flights that are present at the airport is high, it would result in congestion and hence delay.

Link for dataset : https://www.transtats.bts.gov/DL_SelectFields.asp?Table_ID=236

The main drivers of delays are :-
a) the imbalances between demand number of scheduled flights and airport capacity. 
b) the weather conditions (this impacts capacity significantly).
c) the propagation of delays from one flight to another factor.

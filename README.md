#  surfs_up
## project overview
The purpose for this analysis is to compare the temperatures for the months of June and December in Hawaii, we used python to read the data from SQLite database and used pandas  to get statistic of the data.
## Result Analysis
The result are shown in the path  [a relative link](December .png)  and  [a relative link](june.png)
1- The temperature mean between June and December shows that  June is 74.9  higher then December 71.0 .
2- The temperature Standard Deviation of June and December shows that June is 3.2  which is lower than December 3.7 .
3-The temperature min of June and December shows that June is 64.0  which is higher than December 56.0 .
## Summaries
As we can see from the result the temperature is different in June than in  December for example we have higher mean in June than December and even the other statistics is different between them.
Her are two other queries we can do to get precipitation in June and December :
results = session.query(Measurement.date, Measurement.prcp).filter(Measurement.date.contains('-12-') )
results = session.query(Measurement.date, Measurement.prcp).filter(Measurement.date.contains('-06-') )


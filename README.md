# PagerRank on Flight Data

Huge dataset of flight information is available for US domestic flights through Bureau of Transport Statistics website. These flight data can be analyzed to suggest improvements to airlines industry or to airport retail business.

The flight data for the year 2017 is chosen which includes all the domestic flight information in US from Jan 2017 to Dec 2017. The data is stored on Hadoop cluster and processed using Spark.

A flight network is created from the data and Page Rank algorithm is used for advanced anlysis of the data. Idea behind using Page rank algorithm is that, it provides the relative importance of the airports in the network. Using this algorithm, the following aspects are being analyzed:

1. Well connected airports.
2. Arrival airports with most cancelled flights.
3. Airports with most delayed flights.

Results of the analysis is visualized on the US map using Google location APIs and matplotlib (python library).

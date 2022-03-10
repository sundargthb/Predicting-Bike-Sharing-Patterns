# Predicting-Bike-Sharing-Patterns
Build a neural network from scratch to carry out a prediction problem from UCI Machine Learning Database.

# Background
Bike sharing systems are new generation of traditional bike rentals where whole process from membership, rental and return back has become automatic. Through these systems, user is able to easily rent a bike from a particular position and return back at another position.

Currently, there are about over 500 bike-sharing programs around the world which is composed of over 500 thousands bicycles. Today, there exists great interest in these systems due to their important role in traffic, environmental and health issues. Apart from interesting real world applications of bike sharing systems, the characteristics of data being generated by these systems make them attractive for the research.

Opposed to other transport services such as bus or subway, the duration of travel, departure and arrival position is explicitly recorded in these systems. This feature turns bike sharing system into a virtual sensor network that can be used for sensing mobility in the city.

Hence, it is expected that most of important events in the city could be detected via monitoring these data.

# Data Set
Bike-sharing rental process is highly correlated to the environmental and seasonal settings. For instance, weather conditions, precipitation, day of week, season, hour of the day, etc. can affect the rental behaviors.

The core data set is related to the two-year historical log corresponding to years 2011 and 2012 from Capital Bikeshare system, Washington D.C., USA which is publicly available in the Capital Bikeshare system data.

We aggregated the data on two hourly and daily basis and then extracted and added the corresponding weather and seasonal information. Weather information are extracted from Free Metereology.

# Associated tasks
Regression:

Prediction of bike rental count hourly or daily based on the environmental and seasonal settings.
Event and Anomaly Detection:

Count of rented bikes are also correlated to some events in the town which easily are traceable via search engines.
For instance, query like "2012-10-30 washington d.c." in Google returns related results to Hurricane Sandy.
Some of the important events are identified. 1.
Therefore the data can be used for validation of anomaly or event detection algorithms as well.

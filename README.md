# High-Resolution Road Vehicle Collision Prediction for the City of Montreal

## Abstract

Road accidents are an important issue of our modern societies, responsible
for millions of deaths and injuries every year in the world. In Quebec only, road accidents are responsible for hundreds of deaths and tens of thousands of injuries. 
In this paper, we show how one can leverage open datasets of a city like
Montreal, Canada, to create accident prediction models, using state-of-the-art
big data analytics.
Such models could be used in the context of road accident prevention, but also
to identify key factors that can lead to a road accident, and consequently, help
elaborate new policies.

We tested various machine learning methods to deal with the severe class imbalance inherent
to accident prediction problems. In particular, we implemented the Balanced Random Forest algorithm, a variant
of the Random Forest machine learning algorithm in Apache Spark.

Experimental results show that 85\% of road vehicle collisions are detected by our model with a false positive rate of 13\%. These examples identified as positive are likely to correspond to high risk situations.
In addition, we identify the most important predictors of vehicle collisions for the area of Montreal: the count of accidents on the same road segment during previous years, the temperature, the day of the year, the hour and the visibility.

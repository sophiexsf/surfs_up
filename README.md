# Surf's Up

## Overview 

We have been tasked with analyzing the temperature trends in Oahu in June and December to determine feasibility for a year-round surfing and ice cream business. The analysis is based on recorded observations provided in a SQLite database.

## Results

Summarizing the data, which is recorded in the figures below, reveals the following observations:

* The average temperature in June was 74.9° and for December was 71.0°.
* The minimum temperature observed in June was 64° and for December was 56°.
* The standard deviation of temperatures measured in June was 3.26 and for December was 3.74.

![June summary](<./june.png>)
![December summary](<./december.png>)

## Analysis

Comparing June and December temperature observations, we see that the average temperatures are similar, and are separated by little more than one standard deviation. The coldest days in December can be noticeably colder than those in June, but most of the time (above the 25th percentile) the difference is within 4°.

To find out more about whether the climate is suitable for a year-round business, I would consider performing these additional queries:

* Check whether recordings from individual weather stations show unique characteristics which might cast doubt on their accuracy or might help decide on the most suitable location
* Evaluate the year-on-year change in June and December observations to determine whether there are any relevant trends emerging that would impact the business plan 
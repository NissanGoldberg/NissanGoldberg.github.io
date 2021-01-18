---
name: Flight Delay Predictor
tools: [Python, Tensorflow 1.x]
image: https://e3.365dm.com/19/05/768x432/skynews-flight-delay_4680150.jpg
description: Predict the delay time of the plane due to the weather and geographical location of the airport on domestic flights in the USA.
external_url: https://github.com/GeekCSA/Flight-Delays
---

# Flight Delay Predictor

Predict the delay time of the plane due to the weather and geographical location of the airport on domestic flights in the USA.

![](https://e3.365dm.com/19/05/768x432/skynews-flight-delay_4680150.jpg)

There are 2 models:

* Linear Regression
* DNN (offers better results)



The dataset was created by merging 

* weather conditions at each of the US airports every day in 2015  (source: [NOAA](https://www.ncdc.noaa.gov/)).
*  scheduled and scheduled times and departures and the actual airport in which the plane and airport landed on each of the 2015 days of domestic flights in the United States (source: [Kaggle](https://www.kaggle.com/usdot/flight-delays)) .
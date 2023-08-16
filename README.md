# SurfMyths-vs-Data
In this project, I verify or debunk some surf myths and conceptions. I have only started surfing recently, therefore, to compensate for my lack of experience I use data. To be precise, I use wind, wave and weather data to derive features such as Wave Rating, Surf Rating, Sunny Weather.

## Questions:
**1. Is the surf better in winter than in summer?**

*Yes, indeed. Waves are statistically bigger in winter and the wind is more favourable. So go surfing in winter even though its cold*

**2. Is the surf better when its sunny**

*No. Actually, sunny or rainy does not impact the surf much. Interestingly, there is a higher chance of good surf when it's raining, because there are more rainy days in winter (for the US west coast). So don't let bad weather discourage you to go surfing.*

**Summary:** I can use the knowledge gained from this data analysis to motivate myself to go surfing on cold and rainy winter days.

## Detailed description of the Project
### Motivation
Complete

### Data collection
The most cumbersome part of this project was to get the data. To my surprise, the wave data was very easy to come by compared to the weather data. I guess you can't make much money off wave data. It was really difficult to get my hands on weather data. At least for Australia, all the weather data is locked behind the Bureau of Meteorology. That's why I opted for the US. NASA offers free weather data.

### Feature Engineering
To answer the questions, I combined information about wind strength, wind direction and wave size that rates the surf quality from 0-5 for every day.

The free weather data from NASA provided lots of information, but not the simple classification of whether it was a sunny day or not. Instead, this feature had to be created from the average radiation. Cloud coverage reduces the received radiation, thus, leading to a lower daily average radiation. In this way, we could identify sunny days as days where the average radiation is the largest

### Results
Here I should display some results

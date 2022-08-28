# Sensorization and Machine Learning 🤖

## Tabular Playground Series - Apr 2022  

This was a competition on the [**Kaggle**](https://www.kaggle.com/competitions/tabular-playground-series-apr-2022) platform, and in this notebook I present my findings.

---

## 📃| **Introduction**

With the rise of industry 4.0, people who work in the industry have more data than ever, this has given us new challenges to make the right decisions based on the immense amount of data that is generated every day, and has required us to improve our skills and explore new tools such as data analysis and machine learning, this is an example of use.

We have been provided with thousands of sequences (each sixty seconds long) read by biological sensors, these recorded hundreds of participants who could have been in either of two possible states of activity. Can we predict what state a participant will be in from sensor data?

## 🔢| **Objectives**

Build a time-series classification model that can predict the state of a participant (0 or 1) based on the reading made by 12 sensors during 60 seconds.

## 🎯| **Conclusion**

We were able to build a fairly efficient classification model with an excellent generalization capacity. It was quite important to do a good feature-engineering process, because thanks to this we were able to detect predictors that are not usually widely used (such as kurtosis) but that can be a great source of information.
Finally, the objective of this analysis was to show that by making intelligent use of the available data we can extract a lot of value, it is up to us to think of creative ways to use and extract knowledge from it. I am sure that over time we will have more and more data at our disposal, and for this reason it is important to make these methodologies visible and use them before we are overwhelmed by the volume of data.

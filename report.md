\# Report: Predict Bike Sharing Demand with AutoGluon Solution

\#### MENA ALLAH HAHMED HASSANIN

\## Initial Training

\### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?

they needed not to be negative so I made negative values equals to zero

\### What was the top ranked model that performed?

WeightedEnsemble\_L3

![](Aspose.Words.147c1b18-3cc6-4b36-a06d-885a6d338f48.001.png)



\## Exploratory data analysis and feature creation

\### What did the exploratory analysis find and how did you add additional features?

- People rented bike more in some days , months and hours than others 

![](Aspose.Words.147c1b18-3cc6-4b36-a06d-885a6d338f48.002.png)![](Aspose.Words.147c1b18-3cc6-4b36-a06d-885a6d338f48.003.png)


- In weather case 4 ( Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog ) people didn’t rent bikes 

![](Aspose.Words.147c1b18-3cc6-4b36-a06d-885a6d338f48.004.png)

- Few people rented bikes on holidays 
- ![](Aspose.Words.147c1b18-3cc6-4b36-a06d-885a6d338f48.005.png)

Semi equal renting rate among the four different seasons 

![](Aspose.Words.147c1b18-3cc6-4b36-a06d-885a6d338f48.006.png)

\### How much better did your model preform after adding additional features and why do you think that is?

test\_eval enhanced from 1.79828 (original features) to 0.53982 

(adding additional features)


\## Hyper parameter tuning

\### How much better did your model preform after trying different hyper parameters?

test\_eval enhanced from 1.79828 (original features) to 0.71142

(making hyper parameters tuning )

\### If you were given more time with this dataset, where do you think you would spend more time?

I will make more analysis for features and trying another hyper parameters tuning with another values 


\### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.

![](Aspose.Words.147c1b18-3cc6-4b36-a06d-885a6d338f48.007.png)

\### Create a line plot showing the top model score for the three (or more) training runs during the project.

![](Aspose.Words.147c1b18-3cc6-4b36-a06d-885a6d338f48.008.png)

\### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

![](Aspose.Words.147c1b18-3cc6-4b36-a06d-885a6d338f48.009.png)

\## Summary

I have learned and applied many concepts of ML life cycle, tools and development 

- Learn how to deal with kaggle and github
- Learn how to load data on notebook
- Make Exploratory Data Analysis and creating an additional feature
- Using AutoGluon

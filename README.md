# Predict-Blood-Donations
Binary classifier to predict if a blood donor is likely to donate again

## Project Description
"Blood is the most precious gift that anyone can give to another person — the gift of life." ~ [World Health Organization](http://www.who.int/features/qa/61/en/)

Forecasting blood supply is a serious and recurrent problem for blood collection managers: in January 2019, "Nationwide, the [Red Cross](https://www.kjrh.com/news/local-news/red-cross-in-blood-donation-crisis) saw 27,000 fewer blood donations over the holidays than they see at other times of the year." Machine learning can be used to learn the patterns in the data to help to predict future blood donations and therefore save more lives.

In this Project, you will work with data collected from the donor database of Blood Transfusion Service Center in Hsin-Chu City in Taiwan. The center passes its blood transfusion service bus to one university in Hsin-Chu City to gather blood donated about every three months. The dataset, obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Blood+Transfusion+Service+Center), consists of a random sample of 748 donors. 
The task is to predict if a blood donor will donate within a given time window. We will look at the full model-building process: from inspecting the dataset to using the tpot library to automate the Machine Learning pipeline.

## Contents
- Project Description
- Inspecting transfusion.data file
- Loading the blood donations data
- Inspecting transfusion DataFrame
- Creating target column
- Checking target incidence
- Splitting transfusion into train and test datasets
- Selecting model using TPOT
- Checking the variance
- Log normalization
- Training the logistic regression model
- Conclusion


### Language
Python
### Libraries
- pandas
- Numpy
- scikit-learn
- [TPOT](https://github.com/EpistasisLab/tpot)

this project is taken from [DataCamp Projects](https://learn.datacamp.com/projects/646)

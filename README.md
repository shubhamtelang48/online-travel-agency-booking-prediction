
## Online Travel Agency Booking Prediction

The booking process has changed dramatically over the past decade, with more guests choosing to book online rather than direct. While the accessibility of online travel agencies may increase exposure and demand for many hotels, it has been met with an increase in cancellation rates. While cancellations are a familiar foe of the hotel industry, it has been the advent of the "risk free cancellations" campaign put on by online travel agencies that have made it a damaging statistic worthy of a second look.

## Overview
The project comprises all steps of Data Science work broken down as follows:

Data collection and wangling: done in Jupyter Notebook
Exploratory Data Analysis: using python for statistical data analysis
Machine learning: using Python -Random Forests,Bagging and gradient boosting with scikit-learn in Jupyter Notebook


## Roadmap

- Firstly we have to import the pandas,numpy,matplotlib,seabron libraries for EDA purpose
- Get the dataset from kaggle and with help of pandas dataframe and read the csv file
- Find any null values presents in dataset if yes then drop the null value or replace with mean of respective column and also find outlier,replaced with mean or mode.
- After that we find that it is the imbalanced dataset so we have to balanced the dataset.
- Then we have to do feature engineering.
  After feature engineering we have to do normalization.
- put our independent and dependent variable into test train split.
- By using sklearn import the model which we have to test.
- find the best model will give as the good accuracy and f1 score.
- In last find the 5 most important features 


## Finding

- The 219 id number country has largest obervation which is 61%.
- The data is anonymized, so determining the exact country or city to which a consumer plans to travel to is not possible.
- Out of those 61% , 58% of searches are made by consumers also located in same country.
- Therefore, to improve the computational efficiency, we are going to train independent models on 219 country id visitors . 
- Both booking rate(2.8%) and click through rate (4.3%) are extremely low. So, the class are very imbalanced.so we balanced this features by using oversanpling technique
- The most common search adults count is 2-adults
- The most common property star rating is 3 stars. 
- More than 73% of the properties are brand properties
- Around 54% of searches contain staying at Saturday.
- On average, the price_usd that received a click or booking is always lower than those of did not get a click or booking.
- Gradient Boosting algorithm gives best results.



## 🛠 Skills
python,data vidualization,sklearn






# Flight Delay Prediction


## Introduction to business scenario

A travel booking website is working to improve the customer experience for flights that experience delays. The company wants to create a feature to let customers know if the flight will be delayed due to weather when the customers are booking the flight to or from the busiest airports for domestic travel in the US. 

In this project we aim to solve part of this problem by leveraging machine learning to identify whether the flight will be delayed due to weather. Dataset of on-time performance of domestic flights operated by large air carriers. You can use this data to train a machine learning model to predict if the flight is going to be delayed for the busiest airports.

## Dataset

The provided dataset contains scheduled and actual departure and arrival times reported by certified US air carriers that account for at least 1 percent of domestic scheduled passenger revenues. The data was collected by the Office of Airline Information, Bureau of Transportation Statistics (BTS). The dataset contains date, time, origin, destination, airline, distance, and delay status of flights for flights between 2014 and 2018.

The data are in 60 compressed files, where each file contains a CSV for the flight details in a month for the five years (from 2014 - 2018). The data can be downloaded from this link: [https://ucstaff-my.sharepoint.com/:f:/g/personal/ibrahim_radwan_canberra_edu_au/Er0nVreXmihEmtMz5qC5kVIB81-ugSusExPYdcyQTglfLg?e=bNO312]. 

Please download the data files and place them on a relative path. 

Dataset(s) used in this assignment were compiled by the Office of Airline Information, Bureau of Transportation Statistics (BTS), Airline On-Time Performance Data, available with the following link: [https://www.transtats.bts.gov/Fields.asp?gnoyr_VQ=FGJ]. 


## Results

After feature engineering was done on the dataset, it was found that the model performances improved a bit. The model was able to predict some of the negative classes correctly.


## Challenges

. Merging all the 60 csv files and storing it into the working directory.

. Merging the weather dataset with the original dataset.


## Future works

The model performance could be improved if more features can be added to the data like the 'wind speed','air traffic', 'mechanical delays', 'Go-Around' for safe landing, 'waiting for connecting passengers' etc. Moreover, correlation between dataset columns should also be considered and the variables that showed extremely high correlation with each other should be removed. If all these factors can be considered in our analysis, our model performance could meet the business goal perfectly. Also, different classification models can be considered and the best performing model can be used to predict delays.


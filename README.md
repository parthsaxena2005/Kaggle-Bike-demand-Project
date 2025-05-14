
# Kaggle Bike Sharing Demand Project

## Introduction
We are given data related to a Bike Sharing system, involving various features which might be affecting the demand of bike rentals

We are supposed to train a model to predict the demand of bike rentals.

## DATA
The data is stored in hour.csv file which includes several columns, the first 70% of Data was used to train the model and the next 30% to test it.

```bash
  index	      : Serial number of the entries
  date        : Date when the data was recorded
  season      : Season when the data was recorded
  year        : year when the data was recorded
  month       : month when the data was recorded
  hour        : hour when the data was recorded
  holiday     : Weather the particular day was a national holiday
  weekday     : Which weekday was the data recorded
  workingday  : Weather the particular day was a workingday
  weather     : Weather on that day (1 = spring, 2 = summer, 3 = fall, 4 = winter)
  temp        : Temperature that day
  atemp       : What the temperature actually felt like
  humidity    : data of humidity that day ()
  windspeed   : windspeed
  casual      : number of non-registered user rentals initiated
  registered  : number of registered user rentals initiated
  demand      : total rentals

```

## Model
in this Project, I have used Linear Regression model.

## Conclusion
The model was able to attain RMSE score of 0.4062287605380681 and an RMSLE score of 0.3665498821563867 putting this model in the Top 1% of submitted model on kaggle.

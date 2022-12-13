![image](https://user-images.githubusercontent.com/95881308/197412724-3d32f019-969e-4338-bb2b-126346c17040.png)

Image of the 1999 Bridge Creek–Moore tornado, which is the strongest tornado ever recorded, globally. It affected the Oklahoma City, Oklahoma metropolitan area.

### I wanted to see what features from a tornado predict  number of fatalities
* Data: This is a dataset maintained by the National Oceanic and Atmospheric Administration (NOAA) of all recorded tornados since 1951.

## Methods: 
* Model selection: Split data into test and train datasets and evaluate model performance by mean absolute error (MAE). 
* Evaluate performance of random forest (rf), gradient boosting (gb), and xgboosting (xgb) regressor models.  The rf regressor model had the least MAE.
* Tune hyperparamters of rf model via gridsearchcv
* Feature importance: Assess important features of the rf regressor model

## Findings: 

![image](https://user-images.githubusercontent.com/95881308/197559293-dd65eebf-49eb-4194-8ce3-f52ff67d0d5a.png)

* A tornado's magnitude was the most important feature in predicting number of fatalities from a tornado.

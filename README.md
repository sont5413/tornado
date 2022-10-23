![image](https://user-images.githubusercontent.com/95881308/197412724-3d32f019-969e-4338-bb2b-126346c17040.png)

1999 Bridge Creek–Moore tornado, the strongest tornado on record affected the Oklahoma City, Oklahoma metropolitan area

### I wanted to see what features from a tornado predict  number of fatalities
* Data: This is a unique dataset owned by NOAA of all recorded tornados since 1951

## Methods: 
* Model selection: Split data into test and train datasets and evaluate model perforamnce by mean absolute error (MAE). Evaluate performanc of random forest (rf), gradient boosting (gb), and xgboosting (xgb) regressor models.  The rf regressor model had the least MAE.
* Feature importance: Assess important features of the rf regressor model

## Findings 
![image](https://user-images.githubusercontent.com/95881308/197411943-a91149c5-45de-471a-ae10-b06659592272.png)

* A tornado's magnitude was not the most important feature in predicting number of fatalities from a tornado
* The month, time zone, and state were all more predictive power

All else being equal, magnitude should be the most predictive factor, along with length and width of the tornado's path.  Of course, there is variability in what lies in the path of a tornado.  It is not always the case that a tornado's path overlaps with major city centers, major highways, and so on.  

# Obesity Behavioral Risk Factor Prediction Model 

Project Description: The U.S. Department of Health & Human Services dataset for Nutrition, Physical Activity, and Obesity - Behavioral Risk Factor Surveillance System looks at a variety of demographic, physical activity and nutrition risk factors annually.  Of particular interest with the wide breadth of the features was whether a regression model could learn and accurately predict the prevalence of obesity.

## Preprocessing
- Preprocessing included: reading CSV file using Spark, filtering and cleaning data, troubleshooting data types & converted to Pandas Data Frame.  Please see below for the transformation and further details in the notebook. 
![Screenshot 2023-06-08 at 7 16 31 PM](https://github.com/saganaga/Obesity-Prediction-Model/assets/119809729/d06cdb49-5f9d-4332-b705-af2b1be94580)
![Screenshot 2023-06-08 at 7 17 20 PM](https://github.com/saganaga/Obesity-Prediction-Model/assets/119809729/b9e96a27-4ba3-4e97-aa14-2dd4a5585856)
![Screenshot 2023-06-08 at 7 19 32 PM](https://github.com/saganaga/Obesity-Prediction-Model/assets/119809729/14322fc2-3ea7-4af0-8322-09c948e5f73c)

## Technologies
-	pyspark (SparkFiles)
-	sklearn.model_selection (train_test_split)
-	sklearn.preprocessing (StandardScaler) 
-	pandas (scipy.stats) 
-	matplotlib
-	st (tensorflow)

## Needs of this project
- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- writeup/reporting

## Conclusion
The purpose of this project was to determine if key attributes in the dataset could allow a model to predict obesity accurately; data included was overweight classification, physical activity, location, income level, education, gender and race.  Factors that were eliminated from the model were years in which less comprehensive data was collected and nutritional attributes (ie. inclusion of fruits and vegetables in daily diet).  Understanding these metrics will help to appreciate if changing modifiable risk factors has a meaningful impact on the development of obesity.
Regression analysis – neural network optimized model included in final notebook has an R-squared value of 0.83 and an RMSE of 2.96 with a target y variable standard deviation of 7.2.  Our group concluded that this model is able to predict obesity reasonably well.   

## Visualization of Data
<strong><a href="https://saganaga.github.io/Obesity-Prediction-Model/" target="_blank">Obesity Data Visualization</a></strong>

## Hypothetical prediction 
- The model will predict any combination of features and give a percent of adults who have obesity 
![chart-5](https://github.com/saganaga/Obesity-Prediction-Model/assets/119809729/0bec3aac-160a-456b-bcb2-9e31e627b0fd)


## Authors
- Audrey Fermanich [@afermanich87](https://www.github.com/afermanich87)
- Rachel Le Grand [@saganaga](https://github.com/saganaga)
- John Muir [@OutFrontAnalytics](https://github.com/OutFrontAnalytics)
- Courtney Toussaint [@cmtoussaint](https://github.com/cmtoussaint)
- Luke Wunderlin [@lwunderl](https://github.com/lwunderl)

## Acknowledgements

 - [U.S. Department of Health & Human Services](https://catalog.data.gov/dataset/nutrition-physical-activity-and-obesity-behavioral-risk-factor-surveillance-system)

# Obesity Behavioral Risk Factor Prediction Model 

Project Description: The U.S. Department of Health & Human Services dataset for Nutrition, Physical Activity, and Obesity - Behavioral Risk Factor Surveillance System looks at a variety of demographic, physical activity and nutrition risk factors annually.  Of particular interest with the wide breadth of the features was whether a regression model could learn and accurately predict the prevalence of obesity.  


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
Regression analysis – neural network optimized model included in final notebook has an R-squared value of 0.83, standard deviation of 7.2 and an RMSE of 2.96.  Our group concluded that this model is able to predict obesity reasonably well.   

## Authors

- Audrey Fermanich [@afermanich87](https://www.github.com/afermanich87)
- Rachel Le Grand [@saganaga](https://github.com/saganaga)
- John Muir [@OutFrontAnalytics](https://github.com/OutFrontAnalytics)
- Courtney Toussaint [@cmtoussaint](https://github.com/cmtoussaint)
- Luke Wunderlin [@lwunderl](https://github.com/lwunderl)

## Acknowledgements

 - [U.S. Department of Health & Human Services](https://catalog.data.gov/dataset/nutrition-physical-activity-and-obesity-behavioral-risk-factor-surveillance-system)
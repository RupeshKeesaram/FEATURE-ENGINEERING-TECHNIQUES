# FEATURE-ENGINEERING-TECHNIQUES :-

WHAT IS MEANT BY FEATURE ENGINEERING :-

* Feature engineering is the process of using domain knowledge of the data to create features that make machine learning model work.
* If feature engineering is done correctly, it increases the predictive power of machine learning algorithms by creating features from raw data that help facilitate the machine learning process.
* Feature engineering is the most important art in machine learning which creates the huge difference between a good model and bad model.
* Feature engineering also helps in making data more transparent to helping the Machine Learning Model And it aslo creates some extra features to enhance the model & model performance.

### FEATURE ENGINEERING IS ALL ABOUT 4W-1H:
   1. When
   2. Why
   3. What
   4. Where
   5. How
   
   
### LIFE CYCLE OF DATA SCIENCE PROJECT :
   1. Data collection strategy --- from company side, 3rd party Api's
   2. Feature engineering -- Handling missing values 
   3. Feature selection 
   4. Model creation and Training the model
   5. Prediction
 
* Data for data science projects should be collected from different sources or we can say from multiple sources.
* And the data that is missing either it might be a continuous data or it might be a categorical data.

### REASON'S  FOR  HAVING MISSING VALUES:
   1. They hesitate to put down the information like age, salary. 
   2. Survey informations are not that valid .
   3. Some of the people may died ( all the missing data in titanic data set is because of people dying)
 
### TYPES  OF  DATA  MISSING :
   1. Missing completely at Random (MCAR).
   2. Missing data Not at random ( MNAR) - Systemmatic missing values.
   3. Missing at Random (MAR).
   
   
   
## BEST   TECHNIQUES  TO  HANDLE  MISSING  VALUES :-
  1. Mean / Median / Mode replacement
  2. Random Sample Imputation
  3. Capturing NAN Values witha a new feature
  4. End of Distribution Imputation
  5. Arbitary Imputation
  
  
## HANDLING CATEGORICAL DATA  (MISSING DATA)
  1. Frequent category imputation.
  2. Adding new feature to capture NAN values.
 
 
 
## DIFFERENT ENCODING TECHNIQUES :
   1. OneHot Encoding.
   2. Ordinal Number encoding.
   3. Count of Frequency encoding.
   4. Target guided Encoding.
   5. Mean Encoding.
   6. Probability ration encoding.
   
   
# STANDARDIZATION  AND  NORMALIZATION TECHNIQUES
   #### WHY TRANSFORMATION  OF   FEATURES  ARE  REQUIRED : 
   1. Linear regression -- Gradient Descent -- Global Minima
   2. Algorithms like KNN, K means, Hierarichal clustering -- All these algorithms works on euclidian distance.
   3. We don't need to use transformation in decision trees, random forest and xgboost and etc.
   4. In Deep Learning we will using transformation and scalling techniques in concepts such as.
      1. ANN  -- Global Minima, Gradient Descent.
      2. CNN 
      3. RNN
      
   #### TECHNIQUES THAT ARE GOING TO BE DISCUSSED IN THIS NOTEBOOK :-
   1. Normalization and Standadization 
   2. Scaling to mininum and Maximum values.
   3. Scaling to meadian and Qunatities.
   4. Guassian Transformation 
      1. Logarithmic transformation.
      2. Reciprocal Transformation.
      3. Square root Transformation.
      4. Explonential Transformation 
      5. Box Cox Transformation.
   
    

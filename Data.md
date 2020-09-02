1. Data source 

The data which will be used comes from the simple example dataset provided at this [link](https://s3.us.cloud-object-storage.appdomain.cloud/cf-courses-data/CognitiveClass/DP0701EN/version-2/Data-Collisions.csv). the dataset consists of 194673 rows and 38 columns; 

2. Data cleaning

The dataset provided has some missing values especially for the SPEEDING column which have all the rows of 'NaN' value. This column could turn out like a fundamental variable for the prediction. But since it has no usefull information it will be dropped. others independent variable such as WEATHER, ROADCOND, LIGHTCOND have aroung 2% percent of missing value. for this missing value we will try a normalization approch in order to have more data for the analysis.

This folder contains the datasets used in this forecasting workshop.

## Combined EMS_Solcast_data.xlsx
Contains synchronised raw satellite weather data and EMS data for one minigrid.

## imputed_data.csv
This dataset has been created from Combined EMS_Solcast_data.xlsx where missing values have been imputed using the multivariate inputation by chained equations (MICE) method. This dataset is the output of the data_preprocessing.ipynb script.

## panama_data.csv
This dataset contains synchronised weather and load data for three major cities in panama and was taken from [Kaggle](https://www.kaggle.com/datasets/saurabhshahane/electricity-load-forecasting). This will be used in the follow-up exercises.

Variables
- nat_demand: National electricity load
- T2M: Temperature at 2 meters
- QV2M: Relative humidity at 2 meters
- TQL: Liquid precipitation
- W2M: Wind speed at 2 meters
- 
And after the underscore is the city:
- toc: Tocumen, Panama City
- san: Santiago City
- dav: David City
- 
The rest of the variables are:
- Holiday_ID: Unique identification number integer
- holiday: Holiday binary indicator (1 = holiday, 0 = regular day)
- school: School period binary indicator (1 = school, 0 = vacations)

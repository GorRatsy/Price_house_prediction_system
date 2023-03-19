# Price_house_prediction_system

The main goal of this project is to build system that could to predict a house price using different features.
Data include next features:
* status - status of advertisement;
* private pool - mark is there a pool;
* propertyType - type of property that appears in advertisement;
* street - name of street;
* bath - mark is there a bath;
* homeFacts - unit with information about saling house;
* fireplace - mark is there a fireplace;
* city - name of city in which house is located;
* schools - information about schools which are located in the same district;
* sqft - square footage of house;
* zipcode - zipcode of city;
* beds - description about bedrooms in house;
* state - name of state in which house is located;
* stories - number of floors in house;
* mls-id/MlsId - multiple listing system ID;
* target - price of house. 

To reduce time for data extraction from 'homeFacts'-feature there is a ready dataframe 'facts_df.csv'.
And for modeling, if you need to skip EDA stage, you can use 'after_eda.csv'.
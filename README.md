# Rusty_Bargain
Creating a machine learning model to predict used cars market value.

**Objective:** Rusty Bargain used car sales service is developing an app to attract new customers. In that app, you can quickly find out the market value of your car. We were tasked with creating a model for this purpose. We have access to historical data: technical specifications, trim versions, and prices. They are not only interested in the quality of the prediction, but also its speed.

**Method:** For this task we first cleaned the data,  then proceeded to do some EDA, split the data into 3 different datasets, several models were trained and evaluated with the RMSE score as well as their processing time. The best model is chosen at the end and tested on the the test dataset to confirm the results.

**Conclusions:** After having evaluated several models, the CatBoostRegressor model was both the best performer and the fastest. 

# Calgary-Weather-Prediction-
I have used the XGBoost Model as it gave the best performance. 
I deployed the model- **best_model_xgb_hp.pkl**
I used requests to use the **OpenMeteo API to fetch 168 hours of data** 
I used pyodbc to make the database connection with python: Used the **function fetch_and_store_data()** to fetch the data from the api and store it in sql database
I used the function **fetch_data_and_make_predictions()** to get the data that we fetched from api and stored in sql. Then that data is passed into our model and then we are **predicting the predicted_temperature, and the weathercode**. Based on the weathercode, we are generating the Conditions. **predicted_temperature, and the weathercode, and Conditions are being updated in the SQL table** 


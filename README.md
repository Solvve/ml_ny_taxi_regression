# NY_taxi_regression
  New York City Taxi fare prediction with Spark.

We need to predict the fare amount (inclusive of tolls) for a taxi ride in New York City given the pickup and dropoff locations. 

Let’s have a look at locations distributions:

![Visualization NY](https://i.ibb.co/nmJcD2k/ny-viz.png)

For developing the prediction model we will use PySpark ML since we are working with a huge amount of data.

For solving this problem we followed the next steps: 

- Optimization of data storage
- EDA
- Feature engineering
- Modeling
- Evaluation

Outcomes:

- Models:  DecisionTreeRegressor  and GBTRegressor from SparkML package.
- Root Mean Squared Error (RMSE) on test data = 4.1192 (GBT model)

| Model | Naive (average) | Decision Tree  | GBT |
| :---: | :---: | :---: | :---: |
| RMSE | 5.9342 | 4.4000 | 4.1192


# Bike Rental Prediction
The project will involve the prediction of the total number of bikes people rent in a certain hour. The dataset used in this project is taken directly from the [UCI ML repository](http://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset). An hourly count of bike rentals is recorded for the Capital bikeshare system from 2011 to 2012 with corresponding calendar and weather data.

### Results
- Non-linear, tree-based models drastically outperformed linear models on this dataset
- Gradient Boosted Trees (GBT) performed the best out of all baseline regression models tested
- The tuned GBT model yielded a 80% decrease in RMSE compared to the simplest possible model which always predicts the mean of all samples (~17 mins to tune)

### Libraries used
- pandas
- numpy
- matplotlib
- sklearn
- time
- joblib
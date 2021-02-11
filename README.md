# Human-Activity-Recognition
Having a computer determine what activity is performed using a data set recorded on a smartphone.

Data set taken from UCI Machine Learning Repository
https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones#

How the data sets were recorded:

"The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain."



Our model: 

In our model we initialized a Sequential Model and used an LSTM Model as our layer due to the data being a time series data set. We added a dropout layer to avoid overfitting and finally used sigmoid activation in our output layer. This was our primary model.]

In our second model with added more LSTM layers and tweaked the dropout layer to see how it impacted the accuracy of the model.

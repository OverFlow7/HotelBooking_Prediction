# HotelBooking_Prediction
Predicting whether or not a search will result on a booking (Binary Classification)

The dataset is heavily imbalanced , (most of the searchs don't end up booked) So I decided to use random undersampling and oversampling using SMOTE . Predictions are then made with Xgboost ( using class weights to further counter the imbalance)

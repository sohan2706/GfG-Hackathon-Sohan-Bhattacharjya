# GfG-Hackathon-Sohan-Bhattacharjya
This repository contains the code for the hackathon as well the submission csv file

Task: Prediction of 2 labels i.e the likelihood of xyz_vaccine and seasonal_vaccine taken by the people using the given features

Steps: 
       
       1. Combining the train features and train labels into one dataframe
       
       2. Data Cleaning and Feature engineering: Involved dealing with the null values, ambiguous columns and categorical columns in the dataset
       
       3. Training the model on the training data. The model I use was a simple dense neural network classifier
       
       4. Checking average auc roc score using train_test_split from training data
       
       5. Data Preprocessing for the test dataset 
       
       6. Using the trained model to predict the output labels for the test dataset
       
       7. Creating a dataframe for the test outputs and converting it into a csv file

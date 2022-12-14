# Machine Learning with XGBoost Classifier Made Easy.

Hi all. A very warm welcome to my app. 

I have made this app to help you preprocess your dataset and build ML model efficiently with just few simple clicks. 

This app is designed such that it can process any CSV files. To help you better understand how this app works, you may
use the sample data provided and follow along with the instructions below.

You can access this app via the link below.

https://streamlit-classification-ncw.herokuapp.com/

Please note that this app is deployed to Heroku platform and computation power allocated can be low.  As such, I will
recommend you to run this app on your localhost and install required python packages as indicated in requirement.txt.
You can access the source code via this Github repo

https://github.com/cheewoeing/Streamlit_Classification

## 1.1 Upload your CSV file
You can get the sample data via the link below.

https://github.com/cheewoeing/Streamlit_Classification/blob/master/Sample_Data/penguins.csv

Please upload the penguins.csv file that you have just downloaded.

Our objective is to predict the species of the penguins.

## 1.2 Deal with missing data
I have delibetely deleted some fields on the first 4 rows of data. 

Please check "Drop rows with missing data?" and on the drop down menu please select "sex". 

You will notice that first 2 rows has been deleted as their "sex" field is empty.

Also, please check "fill missing data with mean?" and on the drop down menu please select "bill_length_mm". 

You will notice that row 2 and 3 has been filled with mean value of the column.

![Screenshot 2022-08-04 at 5 27 41 PM](https://user-images.githubusercontent.com/104248593/182813461-07afa2c7-9da0-4ba9-b5ac-d76bc1c9565c.png)

Click "Proceed to next step"

## 2.1 Select features(X)
Please select "island", "bill_length_mm", "bill_depth_mm","flipper_length_mm", "body_mass_g" and "sex".

## 2.2 Select label(y)
Please select "species".

## 2.3 One-hot encode features
Please check "One-hot encode features?" and on the drop down menu please select "island" and "sex".

![Screenshot 2022-08-04 at 5 28 37 PM](https://user-images.githubusercontent.com/104248593/182813688-b9d5bcd4-fd0d-4c96-bf13-6a57d0ceb61d.png)

Click "Proceed to next step".

## 3.1 Encode label
Please check "Encode label?"

![Screenshot 2022-08-04 at 5 29 50 PM](https://user-images.githubusercontent.com/104248593/182814021-5f817809-8fef-456d-b812-5d92ff701699.png)

Click "Proceed to next step".

## 4.1 Splitting data into train and test set
Please select the size of the test set as you like. Here I would recommend 0.2.

## 4.2 Scaling features
Please select "bill_length_mm", "bill_depth_mm", "flipper_length_mm", and "body_mass_g".

You can also preview and download X_train, y_train, X_test, y_test in .csv format here

![Screenshot 2022-08-04 at 5 29 50 PM](https://user-images.githubusercontent.com/104248593/182814599-a8137a5d-4ed7-4a47-bb19-f9909b24dfb1.png)

Click "Proceed to next step".

## 5.1 Build and evaluate model
After the model is built, you can view the confusion matrix and tree visualisation.

Once you are satisfied with the result, click "Proceed to next step".

## 6.1 Make prediction with user input
Now our model is ready for making prediction, input the feature values and the prediction will be generated below.

![Screenshot 2022-08-04 at 5 34 29 PM](https://user-images.githubusercontent.com/104248593/182814926-50b5a5cf-2d81-49ce-9799-e16d27885083.png)

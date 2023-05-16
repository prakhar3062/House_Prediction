### Welcome to the Machien Learning Model Project 
In this project, i have trained the ml model using the kaggle dataset(Bengluru_House_Data.csv).Then the model is genrated in the pickle format. Then the model used by the util.py.Then the model(price_prediction_model.ipynb) is used by the api built using the flask python framework in server.py.Beside client contains the frontend which ultimately uses the api.
### Model
For building the model-:
1) Data is colleected from the kaggle and saved in the Bengluru_House_Data.csv file.
2) Data is analyzed a bit and we perform dimensionally reductioon.
3) Removed the outliers Then we divide the dataset into train data and test data
4) Used linear regression Cross Validation is used and shuffle split will randomize
5) Try other Regression techniques we use method grid search cv(api and can run different model)
6) Pickle file is grnerated of the model
7) Then the different columns are generated in the format of JSON file.

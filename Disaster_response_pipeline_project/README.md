# Disaster Response Pipeline Project

### Introduction

In this project, I am going to build disaster response machine learning pipeline to categorize emergency messeges based on the needs communicated by the sender. 
There are three major steps in this project. 

1. ETL Process

    I merge the dataset in the data folder (disaster_messages.csv and disaster_categories.csv), then perform preprocessing techniques to clean the data. Finally cleaned data stored in sqlite database.

2. Training Model

    Using scikit-learn, then I train the classifier to be able to get a model which can classify a message, save the model in the models folder with the name classifier.pkl.

3. Run the Web App

    Using flask, we can run our model and deploy in the website so that people can manually type the message and see its category.


### Instructions:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
        
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go to http://0.0.0.0:3001/

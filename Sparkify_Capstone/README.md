# Sparkify_Capstone_Project

### Project Motivation

As many music streaming services that opreates on dataset with seconds of timeframe, the size of the data grows expotentially large in a short while. The size of the data would quickly outgrown the memory limit of most personal computers. To ensure the analytical activities are still performed as normal, we need to utilize the power of spark to perform a distributed data analytics task to obtain insights for from the data. In particular, we would like to understand the factors that contributes to users churning behaviors.

### Problem Statement
Business problem is to predicting potential customers who will churn or cancels their subscription from Sparkify music service using Pspark.

### File Descriptions

    Sparkify_Capstone_Project.ipynb
        Notebook contains complete work/code related to this project.

    README.md

### Required Packages

    Pandas
    pyspark(sql and ml)
    matplot
    numpy
    Seaborn

### Data Source
Data is readily available in the Udacity workspace

### Derived Features for Model
    Average Number of songs per session
    Registered Duration
    Total Songs
    Number of rollads actions
    Number of thumbs up actions
    Number of thumbs down actions
    Number of friends added
    Number of Songs added to playlist
    Gender
    Premium Level
    Churn Flag

### Model Used
    Random Forest Classifier
    Logistic Regression
    Gradient-Boosted Tree Classifier

### Metrics Used
    F1 Score
    Accuracy

### Work Flow
    Load and Clean Dataset
    Exploratory Data Analysis and Defining Churn Label
    Feature Engineering
    Test Models and Determine Best Model with tuning parameters

### Results
    Detailed observations on the Project are documented on Medium : https://santhoshrathode.medium.com/sparkify-customer-churn-analysis-prediction-7b3e86abc697
    
    
### Acknowledgements
Thanks Sparkify and Udacity group for sharing the dataset required for analysis.



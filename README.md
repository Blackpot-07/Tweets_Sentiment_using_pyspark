# Tweets_Sentiment_using_pyspark
This is a sentiment analysis model that predicts the overall sentiment of a set of tweets, this is programmed to run over a pyspark cluster

# Introduction

The project uses PySpark's huge data handling capabilities to tackle the problem of sentiment analysis at scale. We employed a dataset developed by Stanford University for sentiment analysis, which has four fields: the tweet's ID, its sentiment, its source of sentiment, and the tweet itself. The performance of two machine learning algorithms—Random Forest Classifier and Logistic Regression—is evaluated to determine which one performs better and why. 

# Techniques

The project uses PySpark to do sentiment analysis using a range of algorithms and techniques: 

### Data Preprocessing:
To prepare the text data for analysis, text-cleaning techniques such as tokenization, stopword removal, and stemming are used. 

### Engineering Features: 
Textual input is transformed into numerical characteristics appropriate for machine learning models using Term Frequency-Inverse Document Frequency (TF-IDF) vectorization. 

### Model Training: 
To categorize sentiment, preprocessed data is used to train the logistic regression and linear support vector classifier (linear SVC) models.


# HOW-TO-RUN

1.	You have to upload “MMD_Project.ipynb” on google colab 
2.	Also upload the file with .parquet extension from the side panel of colab on left side
3.	For the dataset you have to enter your Kaggle username & API key. You can get this straight from your Kaggle settings panel
4.	For plotly ensure to install package using “!pip install plotly”
5.	Run the cells sequentially or press RUN ALL in colab panel
6.	Ensure a strong internet connection before running the notebook as it’ll take approx. 2hrs to complete execution

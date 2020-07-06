# udacity_ml_engineer_nano

FOLDER - 0 Software Fundamentals
  - Some basic items on optimizing code and OOP syntax
  - Creating Python packages

FOLDER - 1 Machine Learning in SageMaker
  - Deployment of ML models in Amazon SageMaker 
  - 1.01_Boston Housing - XGBoost - High Level
    - Building a model using Batch Transform in SageMaker - use the Python SDK to interact with SageMaker
  - 1.02_IMDB Sentiment Analysis - XGBoost 
    - Building a model using Batch Transform in SageMaker - use the Python SDK to interact with SageMaker
  - 1.03_Boston Housing - XGBoost - Low Level
    - Building a model using SageMaker
    - Low level approach where we describe different tasks we want SageMaker to perform
    - The high level approach makes developing new models very straightforward, requiring very little code. The reason this can be done is that certain decisions have been made for you. 
    - The low level approach allows you to be far more particular in how you want the various tasks executed, which is good for when you want to do something a little more complicated.
  - 1.04_Boston Housing - XGBoost (Deploy) - High Level
    - Building and Deploying simple model using the Python SDK to interact with SageMaker
  - 1.05_Boston Housing - XGBoost (Deploy) - Low Level
    - Building and Deploying simple model with the low level approach
    - Using the low level approach to deploy our model requires us to create an endpoint, which will be used to send data to our model and to get inference results.
    - In order to create an endpoint in SageMaker, we first need to describe an endpoint configuration. 
  - 1.06_IMDB Sentiment Analysis - XGBoost - Web App
    - Deploy the sentiment model via a web app that
    - Using Amazon Lambda and API Gateway to solve: a) the authentication issue, b) bag of words encoding expected by model vs the block of text in the web app
    - Flow is as following: App <<-->> API & Lamda <<-->> Model
    - App finished product: https://derekspublicbucket.s3.us-east-2.amazonaws.com/index_sentiment.html
    - This app only works when I turn on the model & endpoint in AWS Sagemaker 
    
    

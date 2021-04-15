# FIT5120-Project
Our project aims to help user identify and get out of filter bubble created "unknowingly" through digital media interactions.

## BackendV1.1 
 
1.0- SpringBoot Basic Framework 

1.0- Connecting to Firebase 

1.1- Support with Mybatis(connect with local MySQL)

## Data Pipeline Explaination - 

* The first part of the pipeline is a machine learning model (Neural Network with softmax activation function) trained over 250,000 + news data . The model is saved in .pkl fornat and used as a trained model in second part of the pipeline
* The second part of data pipleline takes input from the user and returns either a cumulative or discreete analysis of the filter bubble created by the news source , i.e Twitter user id.

## System Architecture 
![alt text](https://github.com/JiaqiSong117/FIT5120-Project/blob/sa.PNG?raw=true)

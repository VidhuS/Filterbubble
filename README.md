# FIT5120-Project
Our project aims to help user identify and get out of filter bubble of a user and helps them get out of it

# Key Features are as follows - 
* Filter bubble visualization based on Twitter handle name 
* Comparative analysis and visualization for two or more Twitter handle name. 
* Present Top 10 trending topics in a Demographic region.
* Present top users (with more than 1M followers) and their tweets for a searched topic .
* Filter bubble visualization for users mentioned above.

Please visit the website at https://filterbubble.ga/home.html   Password- alan123



## BackendV1.1 
 
1.0- SpringBoot Basic Framework 

1.0- Connecting to Firebase 

1.1- Support with Mybatis(connect with local MySQL)

## Data Pipeline Explaination - 

* The first part of the pipeline is a machine learning model (Neural Network with softmax activation function) trained over 250,000 + news data . The model is saved in .pkl fornat and used as a trained model in second part of the pipeline
* The second part of data pipleline takes input from the user and returns either a cumulative or discreete analysis of the filter bubble created by the news source , i.e Twitter user id.

## System Architecture 
![System Architecture](https://i.imgur.com/dHyEcFB.png)


## System Artifacts
1. SpringBoot:

SpringBoot will be used as the main framework for the back-end of the project. SpringBoot can quickly build a series of features to quickly respond and handle requests from the front- end.

2. Firebase:

In our project, we mainly use the cloud database, most of the data interaction work can be done in the cloud, the back-end can easily store and access data through the cloud for processing and return to the front-end. At the same time, Firebase comes with a Realtime database function that can make the data processing and call more flexible and help the project to achieve complex functions.

3. AWS/Azure:

AWS/Azure is a popular development platform that helps develop applications that can run on cloud servers, data centres, web and PC. Cloud developers have access to the storage, computing power and network infrastructure services of data centres. Through these cloud-based platforms, programs can better perform data analysis and storage functions.

4. Twitter API:

The project will analyze the user's Twitter feeds and analyze the filter bubble the user is in based on this information. The Twitter API will play an important role in this process, as the web page will have many functions to interact with the Twitter API and implement user authentication and data extraction.

5. News API:

The project uses the News API to search and extract content from news content. The News API will help the web page to better access the news information and help the website to better perform the recommendation function.

## Github framework

1. Back-end Folder

   1.1  SpringBoot
     SpringBoot provides logical operations and database support for filterbubble.ga, and passes information through the API.  All Springboot code has been provided in this folder.

   1.2  Flask
     Flask provides analysis support for filterbubble.ga. This backend mainly integrates with the Twitter analytics module and transfers data via API. The flask used in the project   is provided in this folder.

 2. Data Analysis Folder

     This folder stores code and files related to data (tweet) analysis, including machine learning models and Jupyter Notebook files.

 3. Front-end Folder

     This folder stores the static web files of filterbubble.ga, including the html, css, js and image files used.

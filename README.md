# Recommendations_with_IBM
Project No.5 in the Udacity Data Scientist Nanodegree (Summer 2021) . Design a Recommendation Engine with IBM Watson. IBM has an online data science community where members can post tutorials, notebooks, articles, and datasets. In this project, you will build a recommendation engine, based on user behavior and socialnetwork in IBM Watson Studio’s data platform, to surface content most likely to be relevant to a user.In this assignment, we will be putting our recommendation skills to use on real data from the IBM Watson Studio platform. 


## Introduction

For this project we will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles we think they will like. Below is an example of what the dashboard could look like displaying articles on the IBM Watson Platform.

Though the above dashboard is just showing the newest articles, we could imagine having a recommendation board available here that shows the articles that are most pertinent to a specific user.

In order to determine which articles to show to each user, we will be performing a study of the data available on the IBM Watson Studio platform. Yoe can create your own account to become a part of their community, and get a better understanding of their data by creating an account on the platform here.


![grafik](https://user-images.githubusercontent.com/59873708/122260801-35b60d00-cec3-11eb-95b8-847480bf879d.png)

Though the above dashboard is just showing the newest articles, you could imagine having a recommendation board available here that shows the articles that are most pertinent to a specific user.

In order to determine which articles to show to each user, we will be performing a study of the data available on the IBM Watson Studio platform. 



### Installation:
You need python3 and the following libraries installed to run the project:

- pandas 
- numpy 
- matplotlib 
- pickle

Furthermore, this Python file needs to be stored in the working directory  
- project_tests.py



## Files:

(1) Python Notebook  

    Recommendations_with_IBM_PeterSchuld.ipynb
    Recommendations_with_IBM_PeterSchuld.html
    
(2) Original Data:    

    articles_community.csv
    user-item-interactions.csv
    
(3) Python code file nessessary to run the notebook (Source: Udacity) 

    project_tests.py


## Data Source:

IBM Watson



## Content of the Python notebook 

The project is divided into the following tasks

I. Exploratory Data Analysis

Before making recommendations of any kind, you will need to explore the data you are working with for the project. Dive in to see what you can find. There are some basic, required questions to be answered about the data you are working with throughout the rest of the notebook. Use this space to explore, before you dive into the details of your recommendation system in the later sections.

II. Rank Based Recommendations

To get started in building recommendations, you will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. You will implement this next.

IV. Content Based Recommendations (EXTRA - NOT REQUIRED)

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, you might come up with some extremely creative ways to develop a content based recommendation system. You are encouraged to complete a content based recommendation system, but not required to do so to complete this project.

V. Matrix Factorization

Finally, you will complete a machine learning approach to building recommendations. Using the user-item interactions, you will build out a matrix decomposition. Using your decomposition, you will get an idea of how well you can predict new articles an individual might interact with (spoiler alert - it isn't great). You will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.


### Licensing, Authors, and Acknowledgements

Thanks to Udacity for the starter code and IBM Watson for providing the anonymised data of its users and their interactions on the IBM Watson Studio’s data platform to be used in this project.

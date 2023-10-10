# Retail e-Commerce Analysis & Recommender System
## Introduction

An eCommerce company wants to make better use of their data with the goal of better decision-making and optimized item recommendations for visitors of the website to increase sales. 

## Solution

In order to make better recommendations for the visitors, we were tasked with making an item recommendation system based on the data the client provided.  
There are three approaches when making a recommendation system: 
Collaborative filtering: This type of system uses the past behavior of users to recommend items that similar users have liked. 
Content-based filtering: This type of system uses the characteristics of items that a user has interacted with in the past to recommend similar items. 
Hybrid: To generate suggestions, this kind of system combines content-based filtering and collaborative filtering techniques. 
The figure below showcases how these systems behave: 
![image](https://github.com/Errimy/recommendationsystem/assets/81532862/6c86d54b-6ea1-42cd-adab-b31d3f913a32)

Collaborative filtering is good when recommending for visitors who have a good number of interactions with items but falls short when recommending for visitors who have a low number of interactions. 
In contrary, Content-based filtering is good when recommending items similar to the ones the visitor have already interacted with but fails when recommending to visitors who have interacted with a lot of different items. 
For this reason, we decided to use a hybrid system, Users who have interacted more frequently can benefit from collaborative filtering, which captures patterns based on user behavior. For users with fewer interactions, content-based filtering, which relies on the features of items, can be more effective.

## Architecture
Here is the architecture we followed in order to achieve this project:
![image](https://github.com/Errimy/recommendationsystem/assets/81532862/e70024dc-2e5c-444f-9e4f-c3fa8a024ed6)

The tools used are:
![image](https://github.com/Errimy/recommendationsystem/assets/81532862/8c5ac2b7-1559-40a3-af9d-70d72b1d92c7)

## Machine Learning
### Collaborative Filtering 

Collaborative filtering is a technique commonly used in recommendation systems to make predictions about the preferences or interests of a user by collecting preferences from many users. This repository contains a Jupyter Notebook file hosted on Google Colab that is divided into three main parts.

### Part 1: Data Pre-processing

In this section, the data undergoes thorough cleaning and pre-processing using Pandas. Data cleaning is a crucial step to ensure that the data used for analysis and modeling is accurate and reliable. Pandas provides essential tools for tasks such as handling missing values, removing duplicates, and transforming data into a suitable format for analysis.

### Part 2: Data Analysis

This section delves into a deeper understanding of the dataset through data visualization techniques using Matplotlib. Visualization is a powerful tool for gaining insights from data. By creating visual representations of the data, patterns and trends within the dataset become more apparent. These visual insights are invaluable for making informed decisions during the recommendation system creation process.

### Part 3: Machine Learning

In the final section, the recommendation system is developed using SciPy and Surprise. SciPy is a library in Python used for scientific and technical computing, while Surprise is specifically designed for building and analyzing recommendation systems. The collaborative filtering technique is applied here, where the system makes predictions by seeking similarities between users. This machine learning approach enables the system to generate accurate recommendations.

## Dashboards
We divided our Dashboard into three pages: 
### Overview
In this first page, we have represented the visualizations that provide a high-level summary of key metrics and insights to give a quick understanding of the overall situation. 
![image](https://github.com/Errimy/recommendationsystem/assets/81532862/930d98d5-9719-4342-abf8-0988746eea1e)

### Analysis
We tried to dedicate this page to showcasing key insights and visualizations from our data analysis. 
![image](https://github.com/Errimy/recommendationsystem/assets/81532862/df1d997c-84fa-4374-8302-a8fba1355c77)

![image](https://github.com/Errimy/recommendationsystem/assets/81532862/ee38a7fe-6446-4b90-a67b-ce282406ba2a)

### Events Time Distribution
On this third page, we have displayed visualizations with a temporal scope, enabling us to analyze the distribution of data over time. 
![image](https://github.com/Errimy/recommendationsystem/assets/81532862/4f25b9f7-a76c-4083-bd01-9e244a8b243e)
![image](https://github.com/Errimy/recommendationsystem/assets/81532862/9f77be49-8235-488b-9ecc-acb9d8c906fa)




## Links
For more details, read the full documentation here: https://github.com/Errimy/recommendationsystem/blob/main/Retail%20e-Commerce%20Analysis%20%26%20Recommender%20System%20Documentation.pdf

Download the Collaborative model here: https://drive.google.com/file/d/1K7DFHMLl1WI1Phsarl9etjFmQNoDbI92/view?usp=sharing

Download the Power BI dashboard here: https://drive.google.com/file/d/1P7HD3oZ2M7U2cY5QQ_5tw7-I5Vh5CU2j/view?usp=sharing

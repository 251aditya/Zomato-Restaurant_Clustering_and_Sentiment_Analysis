# [Zomato-Restaurant_Clustering_and_Sentiment_Analysis](https://colab.research.google.com/drive/1RKe9hnr0YLAWDUBy0VDRU7tlWgMFPptU?usp=sharing)
![](zomato.jpg)

## Table of Contents
- [Introduction](#introduction)
- [Problem Statement](#problem_statement)
- [Dataset](#dataset)
- [Installation](#installation)
- [Conclusion](#conclusion)
- [Data Insights](#data_insights)

## Introduction
**Zomato is an Indian restaurant aggregator and food delivery start-up founded by Deepinder Goyal and Pankaj Chaddah in 2008.**

**Zomato provides information, menus and user-reviews of restaurants, and also has food delivery options from partner restaurants in select cities.**

India is quite famous for its diverse multi cuisine available in a large number of restaurants and hotel resorts, which is reminiscent of unity in diversity.

Restaurant business in India is always evolving. More Indians are warming up to the idea of eating restaurant food whether by dining outside or getting food delivered.

***The growing number of restaurants in every state of India has been a motivation to inspect the data to get some insights, interesting facts and figures about the Indian food industry in each city.***

Here we utilize the advanced data analytics techniques to gain a deeper understanding of the restaurants and customer feedback on the popular online food delivery platform, Zomato.

The data includes information such as the restaurant's name, location, cuisines, average cost for two, ratings, and user reviews.

We started with task of data cleaning and preprocessing, which involved the elimination of duplicate entries, addressing missing values and finally making data ready for analysis.

We then implemented clustering on the restaurant data through the use of the k-means algorithm.

The objective of the clustering was to group similar restaurants together and figure out patterns within the data.

The features used for clustering process included the restaurant's location, cuisines, and average cost for two.

The number of clusters was determined by utilizing the elbow method.

Then we conducted sentiment analysis on the user reviews to gain understanding of the overall sentiment towards the restaurants.

Certain libraries were utilized to classify the reviews as positive, negative, or neutral.

We also extracted the most recurrent words utilized in the reviews and visualized them through the creation of word clouds.

The outcome of the analysis revealed that the restaurants within the city were grouped into five clusters based on their location, cuisines, and average cost for two.

The sentiment analysis shows customers held a positive sentiment towards the restaurants.

The insights gained from the analysis can be of immense benefit to both restaurants and customers in making informed decisions.

Furthermore, the project can be extended to other cities or even countries to gain insight into the eating habits and preferences of individuals in different regions.

## Problem_Statement
The Project focuses on Customers and Company, you have to analyze the sentiments of the reviews given by the customer in the data and make some useful conclusions in the form of Visualizations. Also, cluster the zomato restaurants into different segments. The data is vizualized as it becomes easy to analyse data at instant. The Analysis also solves some of the business cases that can directly help the customers finding the Best restaurant in their locality and for the company to grow up and work on the fields they are currently lagging in. This could help in clustering the restaurants into segments. Also the data has valuable information around cuisine and costing which can be used in cost vs. benefit analysis Data could be used for sentiment analysis. Also the metadata of reviewers can be used for identifying the critics in the industry.

## Dataset
The dataset used in this project is sourced from [Zomato Restaurant & Metadata](https://drive.google.com/file/d/1ZdRtAMFQ2leSD8WZBVG8ZTEHli1D7CF5/view?usp=sharing) and [Zomato Reviews](https://drive.google.com/file/d/1EZHHzEmIm9o4zsvRh4vo7PKMwJ4jQSjS/view?usp=sharing) It comprises a comprehensive collection of information related to **Zomanto Restaurant Clustering & Sentiment Analysis**, including:
Restaurant information Dataset:

    Name : Name of Restaurants

    Links : URL Links of Restaurants

    Cost : Per person estimated Cost of dining

    Collection : Tagging of Restaurants w.r.t. Zomato categories

    Cuisines : Cuisines served by Restaurants

    Timings : Restaurant Timings

Reviews of restaurant Dataset:

    Restaurant : Name of the Restaurant

    Reviewer : Name of the Reviewer

    Review : Review Text

    Rating : Rating Provided by Reviewer

    MetaData : Reviewer Metadata - No. of Reviews and followers

    Time: Date and Time of Review
    
## Installation
To run this project on your local machine, follow these steps:

         Copy the colab file into your drive.

         Run the colab file to gain insights.

## Conclusion
Clustering and sentiment analysis were performed on a dataset of customer reviews for the food delivery service Zomato.

The purpose of this analysis was to understand the customer's experience and gain insights about their feedback.

The clustering technique was applied to group customers based on their review text the customers were grouped into two clusters: positive and negative.

This provided a general understanding of customer satisfaction levels, with the positive cluster indicating the highest level of satisfaction and the negative cluster indicating the lowest level of satisfaction.

Sentiment analysis was then applied to classify the review text as positive or negative.

This provided a more detailed understanding of customer feedback and helped to identify specific areas where the service could be improved.

Overall, This analysis provided valuable insights into the customer's experience with Zomato, and it could be used to guide future business decisions and improve the service.

Additionally, by combining clustering and sentiment analysis techniques, a more comprehensive understanding of customer feedback was achieved.

## Data Insights
We figured out the top 10 most expensive restaurant in the given dataset , and they are :-

"Collage - Hyatt Hyderabad Gachibowli

Feast - Sheraton Hyderabad Hotel Jonathan's Kitchen - Holiday Inn Express & Suites 10 Downing Street Cascade - Radisson Hyderabad Hitec City Zega - Sheraton Hyderabad Hotel Republic Of Noodles - Lemon Tree Hotel Mazzo - Marriott Executive Apartments Arena Eleven Barbeque Nation"

We figured out the top 10 most Economical restaurant in the given dataset , and they are :-

"Mohammedia Shawarma

Amul Asian Meal Box Sweet Basket KS Bakers Momos Delight Hunger Maggi Point Wich Please Shah Ghouse Spl Shawarma Tempteys"

We figured out that their are different hotels which sells different types and number of cuisine among them, we have "hunger maggie point" who serves minimum number of cuisines and "Beyond Flavours" being the one serving maximum number of cuisines.

We could see that their are restuarants having high price are being equally reviwed or rated as bad and good, however we could see more data from 2018 and 2019 spread across.

we could conclude that zomato has some tagged collections which makes it easier for the user to get through the desired food they are looking for , so in order for the business to grow , the restaurant should focus to getting more tags from zomato and keep availability accordingly.

We could figure out that their are certain cuisine which are available only in certain months like healthy food , mexican , arabians , kebab.however most of the cuisines are available during all the months.

We found that , the reviewer that reviewed "Pista House" restaurant has the highest number of followers and one who reveiwed "Dunkin's Donuts" had lowest number among top 5 category.

We could see that their are restuarants having high price are being equally reviwed or rated as bad and good, however we could see more data from 2018 and 2019 spread across.

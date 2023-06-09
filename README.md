# Zomato-Restaurant-Clustering-and-Metadata-Sentiment-Analysis

![image](https://user-images.githubusercontent.com/120029190/230609933-f81281e1-4c8a-4910-9068-5487e0d467b4.png)


## Project Summary
Zomato is an Indian restaurant aggregator and food delivery start-up founded by Deepinder Goyal and Pankaj Chaddah in 2008. Zomato provides information, menus and user-reviews of restaurants, and also has food delivery options from partner restaurants in select cities.

The Zomato Restaurant Clustering and Sentiment Analysis Project is a machine learning project that involves clustering restaurants based on their features and performing sentiment analysis on customer reviews. The project uses unsupervised learning techniques to group similar restaurants and identifies patterns and similarities among them. Additionally, sentiment analysis is performed on the reviews of each restaurant to classify them as positive, negative, or neutral. The insights gained from this project can be useful for restaurant owners to understand customer preferences and improve their services accordingly. The Project focuses on Customers and Company, you have to analyze the sentiments of the reviews given by the customer in the data and make some useful conclusions in the form of Visualizations. Also, cluster the zomato restaurants into different segments: The data is visualized as it becomes easy to analyses data at instant The Analysis also solves some of the business cases that can directly help the customers finding the best restaurant in their locality and for the company to grow up and work on the fields, they are currently lagging in. This could help in clustering the restaurants into segments. Also, the data has valuable information around cuisine and costing which can be used in cost vs. benefit analysis Data could be used for sentiment analysis. Also, the metadata of reviewers can be used for identifying the critics in the industry.

## Problem Statement
The restaurant industry is highly competitive and dynamic, with new restaurants constantly entering the market. Restaurant owners face the challenge of understanding customer preferences and meeting their expectations to stay relevant in the market. In this context, there is a need for a data-driven approach that can help restaurant owners gain insights into customer preferences and improve their services accordingly. The Zomato Restaurant Clustering and Sentiment Analysis Project aims to address this problem by leveraging machine learning techniques to cluster restaurants based on their features and perform sentiment analysis on customer reviews to identify areas of improvement.

##  Understanding The Datasets

**Restaurant Data**

---


|**Fields** | **Description**|
|-----------|--------------|
Name | Name of Restaurants
Links | URL Links of Restaurants
Cost | Per person estimated cost of dining
Collections |Tagging of Restaurants with respect to Zomato categories
Cuisines|Cuisines served by restaurants
Timings|Restaurant timings

---


**Review Data**


---


|**Fields** | **Description**|
|-----------|--------------|
Reviewer|Name of the reviewer
review|Review text
Rating|Rating provided
MetaData|Reviewer metadats-No of reviews and followers
Time|Date and Time of Review
Pictures| Number of pictures posted with review


## Data Wrangling & Data Preprocessing
### Overall Insights From Zomato Restaurant Names and Metadata.csv

* This dataset has a shape of (105, 6) with 54 null values in ‘Collection’ column and 1 null values in ‘Timing’ column.
* There are 44 different/unique Cuisines present in our dataset.
* There are 33 restaurants with 3 different cuisines, 26 restaurants with 2 different cuisines, 21 restaurants with 4 different cuisines, 12 restaurants with 5 different cuisines, 12 restaurants with only 1 cuisine and only 1 restaurant with 6 different cuisines.
* North Indian is the mostly available food on 61 number of different restaurants followed by Chinese and Continental food which is available on 43 and 21 restaurants. It means mostly people demands for this food as compared to other food like pizza, juices, malaysian food which is available on less number of restaurant.

.

.

.

.

And many more are there. You can refer my colab for more interesting insights!!!

### Overall Insights From Zomato Reviews Data.csv
* From this dataset, we found that 5 star is the highest rating given by 3832 number of customer. At the same time, Lowest rating given by the customers is 1.5 star.
* We analyses the Top 20 Popular customers (With Highest number of followers) and their order timings. Here we got to know that Satwinder Singh has the highest number of followers with 13410 followers, followed by Eat_vth_me who has slightly less number of 13320.
* We found Top 20 Popular customers and restaurants (With Highest number of Review_count). Anvesh Chowdary has posted a high number of reviews i.e. 1031 reviews, while the hotel named Collage - Hyatt Hyderabad Gachibowli, Pista House and Labonel has 1031 number of reviews count.

.

.

.

.

And many more are there. You can refer my colab for more interesting insights


# Data Visualization & Hypothesis Testing
Data visualization is used to present the findings in the form of ten different charts, including univariate, bivariate, and multivariate visualizations. These visualizations help in understanding the relationships between different variables and the overall trends in the data. 
Some of the importanat visualizations are -
1. **Distribution of the ratings column:**

![image](https://user-images.githubusercontent.com/120029190/230606443-bef6197f-9f22-4eec-aad3-f348f08a8657.png) 

2. **Distribution of final column sentiments:**

![image](https://user-images.githubusercontent.com/120029190/230606469-8574f06a-7fb0-42e2-a51c-671cb7757bdd.png)

3. **No. of orders over different time slot:**

![image](https://user-images.githubusercontent.com/120029190/230606646-51ec4be6-0861-45b5-9212-de524f2d4992.png)



# Model Implementation

1. K-Means Clustering
2. Hierarchical Clustering (Agglomerative)
3. DBSCAN Clustering
4. PCA (Principal Component Analysis)
5. Content Based Recommendation System

# Best and Final Model
DBSCAN (Density-Based Spatial Clustering of Applications and Noise) is the most
suitable algorithm for our project because restaurants in a given area may have varying
densities, and the number of restaurants may not be known in advance. DBSCAN can
discover the optimal number of clusters by detecting regions of high density and identifying
clusters as regions with a high density of points. You can see below the clear visualization of the DBSCAN model.

![image](https://user-images.githubusercontent.com/120029190/231064321-1fd2d811-2833-4568-8ac1-78175111a5ca.png)


# Advantages & Future Work 
* AI technology can be leveraged to analyze customer reviews and ratings, helping to quickly
identify patterns regarding customer satisfaction, dissatisfaction and specific customer trends.
* Automated customer review analysis can provide quick and accurate feedback from customers,
helping to identify potential problems in the restaurant’s service delivery or customer experience.
* AI-driven analysis of customer reviews can be further used to make improvements to menus,
pricing, services and quality of food.
* Restaurateurs can get valuable insights into which dishes and ingredients are most popular and this
in turn can help create more appealing menus and offer better value for customers.
* AI also helps restaurants target customers with offers and discounts based on their priorities.


# Conclusion
The conclusion of this Zomato restaurant clustering and metadata sentiment analysis project is that it is possible to use natural language processing and machine learning algorithms to build a model that can accurately cluster restaurants based on their reviews and sentiments. This project has helped identify customer preferences and restaurant ratings in order to better understand the impacts of customer feedback on the restaurant industry. This model can then be used to improve the decision-making process of a restaurant owner or manager in terms of advertising, pricing, customer acquisition, and other important business decisions. With this data, business owners can make more informed decisions about the quality of their restaurants and better understand the customer experience. We have seen that AI-based solutions provide a powerful tool for business owners to gain insight into the performance of their restaurants. After that sentiment analysis can be used to gain insights into customer preferences, providing data-driven understanding into how customers perceive different aspects of service quality. Furthermore, the insights provided by this project can be used for further business growth strategies.



# THANK YOU 

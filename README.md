# **Instacart Recommendation System**

The task at hand for this project was to build a model that adds value by solving a problem. 

In my case, I set out to work on something I hadn’t done before, as a way to work outside my comfort or knowledge zone. When the description of the final capstone mentioned some popular platforms recommendation systems, I thought that would be the perfect opportunity to flex my everything is figureoutable muscle. I found data Instacart released for orders from 2017 and knew this was the perfect opportunity to add value during a time when more people are turning to online grocery shopping and delivery.  

Instacart, if you’re unfamiliar, is a platform, available through an app or website, that allows customers to order groceries, for pick up or delivery, from participating retailers with the shopping being done by a personal shopper. 

Two different models were testest, each based off of a weighted rating. Normally a weighted rating would need a rating from users. Being that I didn’t have a metric like that, I chose to create this score two different ways. The first weighted score was based on quantity of each product purchased and the second based on the amount of orders a product was ordered in. The order based model was the better performing model.


Analyzed data included Data for
*   62,000 Orders
*   41,000 Customers
*   134 Aisles
*   31,728 Products

The data comes from Kaggle and can be found [here](https://www.kaggle.com/c/instacart-market-basket-analysis/data). 

Skills:  Pyspark, Cosine Similarity, Alternating Least Square Matrix Factorization, Collaborative Filtering, Data Merging, Hyperparameter Testing, Google Data Studio Dashboard, Data Visualization

View my Google Data Studio Dashboard for this project [here](https://datastudio.google.com/u/0/reporting/714b6b6e-bf81-4025-8673-da32cdc95a76/page/LuBV).

**Works Cited**

Instacart. “Instacart Market Basket Analysis | Kaggle.” Kaggle, Instacart, 2017, www.kaggle.com/c/instacart-market-basket-analysis/data.

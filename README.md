# Wine-Shop-Transactions - TASKS

Employed Python to use K-means clustering to explore the dataset of 6000 transaction from a wine shoppe. 

Provided any insight from your exploration that will be beneficial to a potential wine shoppe owner.
Perform k-mean clustering with 3 clusters using the following variables.
a. Satisfaction
b. quality
c. price
d. margin on a dollar

Performed the following tasks.
1. Explored the dataset using K-means clustering. Perform K-mean clustering 

2. Selected one of the clusters that I deemed significant/interesting and described that
cluster and described why that cluster is interesting/significant.

3. Performed a further  Logistic Regression analysis on that cluster. Described and
explained the results/output of my analysis.

RESULTS

The 3 clusters are split into:
•	Cluster 1: 2722 observations 
•	Cluster 2: 2377 observations
•	Cluster 3: 1398 observations

Despite Cluster 2 having the lowest mean price, it also has the lowest average Quality rating (8.32), Satisfaction rating (5.76), Price ($4.41) and the least Margin on the dollar ($0.39). Though the customers who populate this cluster might be purchasing wine due to their lower cost, they do not like them as is evidenced by the low Quality and satisfaction ratings. The Wine Shoppe also does not make a lot of Margin on the Dollar from this cluster of customers.

Cluster 1 is better than Cluster 2 since it has a better average Quality Rating (8.99), Satisfaction rating (7.94), Price ($5.55) and Margin on the Dollar ($0.55). This shows that the customers who populate this cluster are willing to pay a higher price and are fairly satisfied with their purchase.

Selecting Cluster 3 as the most Interesting Cluster


Cluster 3 with the least number of observations (1398) is the most interesting cluster of the 3. This is because it is the most expensive at an average price of $6.75, yet it has the average highest Quality rating (16.1), Satisfaction rating (8.84) and the highest margin on the dollar ($0.56). The customers who fall into this category are willing to pay a premium for their wine and are very well satisfied by them.

While it  is clear and important for the Wine Shoppe to continue to service this wide-array of customers, they should focus their energy on the customers that fall into Cluster 3 in order to increase the size of the population. Doing this will increase the Wine Shoppe’s revenue and their profit margins.



Post-Clustering Analysis (Regression)


•	I conducted a further analysis on Cluster 3 using a Multiple Regression model.
•	I used Margin on the Dollar as the Target variable of the model.
•	The input variables were - Price, Quality rating and Satisfaction rating.

Explaining the Results of my analysis


The p-value of the model (<0.0001) shows that the model is statistically significant.

Based on their p-values which are less than the significance level of 0.005, the following input variables influence the Margin on the Dollar:
•	Price of the wine: <0.0001
•	Quality Rating: 0.0065
•	Satisfaction Rating: <0.001

The R-square (0.1561) indicates that approximately 15.61% of the variation in the dependent variable (Margin on the dollar) is explained by the input variables in the model. 
•	This means that the remaining 84.39% is influenced by other variables not included in the model. 
•	The Margin on the Dollar is a complex enough phenomenon that a model that explains 15.61% variance can be useful.


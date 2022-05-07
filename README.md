# Cryptocurrencies
## Purpose
The purpose of this analysis was to determine which cryptocurrencies are actively traded on the trading market and how they can be grouped to create a classification system for investment.
## Results
First, an elbow curve was created in order to find the best value for K so that we could use the K-means algorithm to predict the clusters.

![image](https://github.com/msaunders0/Cryptocurrencies/blob/main/Resources/elbow.png)

Given the results, 4 clusters were identified and used to classify the cryptocurrencies in question. Then, a scatter plot was used to visualize the results.

![image](https://github.com/msaunders0/Cryptocurrencies/blob/main/Resources/3dclass.png)

A total of 532 cryptocurrencies were indentified. Most of the cryptocurrencies fell into Class 0 or 3. Classes 1 and 2 appeared to be outliers, but there is not enough data to explain why. A larger snapshot of historical data would be needed in order to determine which, if any, of these cryptocurrencies would be feasible as investment vehicles.

![image](https://github.com/msaunders0/Cryptocurrencies/blob/main/Resources/scatter.png)

# Problem Statement Perform clustering (Hierarchical,K means clustering and DBSCAN) for the airlines data to obtain optimum number of clusters
+ Clustering analysis is an unsupervised learning method that separates the data points into several specific bunches or groups, such that the data points in the same groups have similar properties and data points in different groups have different properties in some sense.

+ It comprises of many different methods based on different distance measures. E.g. K-Means (distance between points), Affinity propagation (graph distance), Mean-shift (distance between points), DBSCAN (distance between nearest points), Gaussian mixtures (Mahalanobis distance to centers), Spectral clustering (graph distance), etc.

+ Centrally, all clustering methods use the same approach i.e. first we calculate similarities and then we use it to cluster the data points into groups or batches. Here we will focus on the Density-based spatial clustering of applications with noise (DBSCAN) clustering method.

## 1) Case Summary
East-West Airlines is trying to learn more about its customers. Key issues are their flying patterns, earning and use of frequent flyer rewards, and use of the airline credit card. The task is to identify customer segments via clustering. The file EastWestAirlines.xls contains information on 4000 passengers who belong to an airline’s frequent flier program. For each passenger the data include information on their mileage history and on different ways they accrued or spent miles in the last year. The goal is to try to identify clusters of passengers that have similar charactersitics for the purpose of targeting different segments for different types of mileage offers.

### 1.1 Data Description: <a class="anchor" id="1.1"></a>
 
The file EastWestAirlinescontains information on passengers who belong to an airline’s frequent flier program. For each passenger the data include information on their mileage history and on different ways they accrued or spent miles in the last year. The goal is to try to identify clusters of passengers that have similar characteristics for the purpose of targeting different segments for different types of mileage offers

+ ID --Unique ID

+ Balance--Number of miles eligible for award travel

+ Qual_mile--Number of miles counted as qualifying for Topflight status

+ cc1_miles -- Number of miles earned with freq. flyer credit card in the past 12 months:
+ cc2_miles -- Number of miles earned with Rewards credit card in the past 12 months:
+ cc3_miles -- Number of miles earned with Small Business credit card in the past 12 months:


+ <b>Note</b>: 
1 = under 5,000
2 = 5,000 - 10,000
3 = 10,001 - 25,000
4 = 25,001 - 50,000
5 = over 50,000


+ Bonus_miles--Number of miles earned from non-flight bonus transactions in the past 12 months

+ Bonus_trans--Number of non-flight bonus transactions in the past 12 months

+ Flight_miles_12mo--Number of flight miles in the past 12 months

+ Flight_trans_12--Number of flight transactions in the past 12 months

+ Days_since_enrolled--Number of days since enrolled in flier program

+ Award--whether that person had award flight (free flight) or not

# Clustering
Help is an International Humanitarian NGO, fighting poverty and providing the people of backward countries with basic amenities and relief during the time of disasters and natural calamities. After the recent funding programmes, they have been able to raise around $ 10 million. 
The problem statement involves choosing the countries which are in direst need of aid based on various factors like income, life expectancy, child mortality, imports, exports etc. 
First the data was imported and Exploratory data analysis was performed on the data by plotting histograms and also checking which country had the highest child mortality, where Haiti was the highest. 
The columns export, import, health and child mortality were a percentage of GDP, so that was converted to its absolute values. 
The data was then checked for the Hopkins score which came above 80%, which shows its good for clustering. 
Outliers were capped. 
The silhouette score was found and the elbow curve was plotted to find out the number of clusters to be chosen. 
After the clusters were formed, the cluster with highest child mortality, lowest GDP and lowest income was chosen and the top 5 countries from that were chosen.  
Those are Haiti, Sierra Leone, Chad, Central African Republic and Mali which are lacking in socio-economic and health factors. 
After doing k means and hierarchical clustering we found out that 3 clusters are optimum to find out the final list of countries. For hierarchical clustering, complete linkage was more useful to find out the number of clusters than single linkage.

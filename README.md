# 18_Cryptocurrencies

## Results

The data that is initially given is not ideal so it was first processed to fit the machine learning models. Since there is no known output, unsupervised learning was used. To look at the difference cryptocurrencies, it was decided to use a clustering algorithm. 

Python was used as the tool for this analysis and divided into four parts: Processing the Data for PCA, reducing the data dimensions using PCA, clustering cryptocurrencies using K-means, and finally visualizing cryptocurrencies results.

The first visualization that was made was through the use of and elbow curve to determine the cluster count:
![]()

Data was combined and a 3D-scatter plot was made with the PCA data and the clusters:
![]()

Finally, a hvplot.scatter plot was created using x=Total Coins Mined and y=Total Coin Supply:
![]()

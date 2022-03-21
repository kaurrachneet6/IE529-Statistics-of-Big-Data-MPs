# Distributed-K-means
This project is an implementation of Distributed k-Means Clustering on General Topologies.

In the era of big data, centralized algorithms like k-means and k- medians need to be scaled to distributed settings. 

Since we cannot transfer the whole dataset from each node to centralized node, we define a coreset. Transfering just the coresets save a considerable amount of communication cost.

The k means cost obtained was as low as the one obtained by running Lloyd’s algorithm on the global dataset whereas the communication cost for the coreset algorithm was considerably less.  

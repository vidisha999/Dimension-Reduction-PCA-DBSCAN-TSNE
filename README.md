# Dimension-Reduction-PCA-DBSCAN-TSNE
We explore the the concept of clustering, where one tries to find groups or clusters of data points.
We also implement dimension reduction techniques such as PCA, DBSCAN, agglomerative clustering and TSNE and compare which technique suits what kind of data and how to pick the ideal dimension technique based on the available datasets.
We use 3 datasets to check the performace of these techniques and the findings are as below:
Interpretation of DBSCAN vs Kmeans on reduced delta set:
                  In k-means we can see many outliers within clusters while in dbscan the outliers are reduced and
                  clusters more closely defined. Clearly we can see that DBSCAN performs better.
Interpretation of K means vs DBSCAN vs Hierarchical Clustering(Agglomerative)
                  We see that for large number of dimensions dataset, K means worked well in comparision to
                  dbscan and agglomerative. However, in dbscan it is givng an optimal cluster value based on eps
                   and min samples unlike K means.
Interpretation of PCA vs TSNE
                  PCA is trying to find the dimensions with maximum variance and preserving those, whereas TSNE
                  is reducing the dimensions based on clusters , thereby presereving the non linear variance in the
                  dataset as well.


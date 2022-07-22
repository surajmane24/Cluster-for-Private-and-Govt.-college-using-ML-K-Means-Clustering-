# Cluster-for-Private-and-Govt.-college-using-ML-K-Means-Clustering

        The K-means algorithm is one of the most influential clustering algorithms in the field of data mining. 
    It is widely used in many fields, such as school, daily consumption, transfer, and curriculum arrangement of different student groups. 
    However, the traditional k-means algorithm is relatively sensitive to the initial cluster center, 
    and the clustering result is excessively dependent on the initial center. In order to obtain a more accurate clustering result, 
    we propose a k-means algorithm based on semantic improvement. In this paper, we calculate the mesh density of the sample, 
    set the density threshold to remove the outliers, and divide the core points, boundary points, noise points, 
    optimized clusters according to the grid density of the data points, effectively reduce noise interference, 
    and build the semantic relationship of the data in the cluster and optimizes the selection of the initial cluster center point. 
    The simulation experiment is carried out by using five common datasets provided by the UCI database. 
    The results show that the search method based on the improved k-means algorithm is reduced in the data iteration time compared with the prior art. 
    Improvements have been made in terms of accuracy.
    
        For this project we will attempt to use KMeans Clustering to cluster Universities into two groups, Private and Public.
        
        It is very important to note, we actually have the labels for this data set, but we will NOT use them for the KMeans clustering algorithm, 
    since that is an unsupervised learning algorithm
    
        When using the K Means algorithm under normal circumstances, it is because you don't have labels. 
    In this case we will use the labels to try to get an idea of how well the algorithm performed, but you won't usually do this for Kmeans, 
    so the classification report and confusion matrix at the end of this project don't truly make sense in a real world setting!.
 



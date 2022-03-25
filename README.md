## First Part: Clustering and GMM model

In this part, we will determine a reasonable number of clusters inside a given
data set, using K-means as the clustering algorithm, and two different perfor-
mance evaluation method to decide on the optimal parameter k, the Elbow
method, and Silhouette score. After that, we construct a Gaussian Mixture
Model and fit the given data set.
1.1 Elbow Method
The Elbow method which runs K-means clustering on the data set for a range
of values for k (say from 1-10), plots the curve of the average score for the model
depending on values for k. We will choose the optimal K at which the addition
of clustering stops giving significant improvement of the score, where the ”el-
bow” happens in the curve.The score metric applied for this method, amongst
many, is the WCSS score, the sum of square distances from each point to its
assigned center. Applying this score metric, a lower score indicates a tighter
clustering scheme, and hence a better performing model.
The metric used for the Elbow method is within-cluster sum-of-squares (WCSS).

## Second Part: Classification
The K-nearest neighbors (KNN) algorithm is a type of supervised machine learn-
ing algorithms. We will explore the theory behind KNN algorithm, and address
some problems that often occur in its implementation. Then, we will build a
Python module that gives us a KNN classifer for a training data set, and also
solve some of the problems discussed before.

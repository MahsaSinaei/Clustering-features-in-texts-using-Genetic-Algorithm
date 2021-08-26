# Clustering features in texts using Genetic Algorithm #

Use the Genetic Algorithm to select features in texts and reduce the number of features by clustering them. The fitness function calculates the information loss using the information theory formula and picks the cluster with less information loss as the best chromosome. After optimization, the KNN classifier is implemented on reduced data to see the performance of this feature selection method. The Reuters-21578 dataset was used in this program.

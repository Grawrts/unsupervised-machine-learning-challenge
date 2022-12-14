# unsupervised-machine-learning-challenge
In this dataset I am using unsupervised machine learning to determine the best way to cluster patients with myopia. I was provided with the raw data, first preparing it by removing the column of "Myopic" so the model wasn't biased. Then I used standard scaler to scale the data so differences in values didn't skew the data.
After the data was cleaned, I performed dimensionality reduction with PCA and then further reduced the dimensions with t-SNE. Showing a scatterplot of the t-SNE results indicated 5 distinct clusters. 
From there, I performed a cluster analysis with K-Means to determine which value of k was at the elbow. This told me that three clusters would really be the best way to cluster this data.
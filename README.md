# spectranet
## Objective
To learn about hyperspectral image analysis, and what hyperspectral image analysis is.

I have compared the performance of CNN and other Clustering algorithms.

Dataset: https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes#Pavia_Centre_and_University

## Observations
1. Accuracy of the CNN model: 92%

I have tried out with K-Means and Gaussian Mixture Model, respectively the silhouette scores are as follows:

2. K-Means Silhouette Score: 0.36

3. Gaussian Mixture Silhouette Score: 0.14

A silhouette score closer to 1 indicates that the clusters are well-separated, while a score closer to -1 suggests that the data points may have been assigned to the wrong clusters. A score around 0 indicates overlapping clusters.

On an overview, while the chosen clustering algorithms did not perform as well as the CNN, they have done okay.

## Thoughts
My initial idea was to implement a DBSCAN clustering algorithm but I was not able to do so as it is computationally intensive, and it figures out the clusters on its own. 
Colab Pro crashed every single time. Will figure out the memory issues and try it out one day.

I came across two clustering algorithms which were new to me, BIRCH and Mean-Shift clustering algorithm. The same goes here, as they were computationally intensive and Colab Pro crashed.

But, on the whole, I understood what hyperspectral image analysis is, and implemented and evaluated a few models for classifying the same.

My next steps would be to learn how to convert an image to a hyperspectral image using GANs, say a landscape/farm overview and the goal is to bin them respectively. 
I don't know if this is a good thing to learn but I want to try.

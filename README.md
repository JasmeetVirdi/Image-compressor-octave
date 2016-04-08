# Image-compressor-octave
--> ex7.m - run this script on your octave terminal to will implement the K-means algorithm and use it
for image compression.

The K-means algorithm is a method to automatically cluster similar data
examples together. Concretely, you are given a training set {x (1) , ..., x (m) }
(where x (i) ∈ R n ), and want to group the data into a few cohesive “clusters”.
The intuition behind K-means is an iterative procedure that starts by guess-
ing the initial centroids, and then refines this guess by repeatedly assigning
examples to their closest centroids and then recomputing the centroids based
on the assignments.
You will use the K-means algorithm to select the 16 colors
that will be used to represent the compressed image. Concretely, you will
treat every pixel in the original image as a data example and use the K-means
algorithm to find the 16 colors that best group (cluster) the pixels in the 3-
dimensional RGB space. Once you have computed the cluster centroids on
the image, you will then use the 16 colors to replace the pixels in the original image.(bird_small.png)

********
ex7.m - Octave/MATLAB script for the first exercise on K-means
ex7 pca.m - Octave/MATLAB script for the second exercise on PCA
ex7data1.mat - Example Dataset for PCA
ex7data2.mat - Example Dataset for K-means
ex7faces.mat - Faces Dataset
bird small.png - Example Image
displayData.m - Displays 2D data stored in a matrix
drawLine.m - Draws a line over an exsiting figure
plotDataPoints.m - Initialization for K-means centroids
plotProgresskMeans.m - Plots each step of K-means as it proceeds
runkMeans.m - Runs the K-means algorithm
[ ] pca.m - Perform principal component analysis
[ ] projectData.m - Projects a data set into a lower dimensional space
[ ] recoverData.m - Recovers the original data from the projection
[ ] findClosestCentroids.m - Find closest centroids (used in K-means)
[ ] computeCentroids.m - Compute centroid means (used in K-means)
[ ] kMeansInitCentroids.m - Initialization for K-means centroids

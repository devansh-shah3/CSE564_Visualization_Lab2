# CSE564_Visualization_Lab2

Goal: practice the basic visualization tools used in visual analytics
  - client-server system: python for processing (server), D3 for VIS (client)

Task 1: basic dimension reduction and data visualization with PCA
  - use PCA to compute the Eigenvectors of the data and visualize the Eigenvalues as a scree plot
  - add an interaction element into the scree plot that allows the user to mark and select the intrinsic dimensionality index (di)
  - plot the data into a PCA-based biplot

Task 2: visualize the data with a scatterplot matrix
  - use the PCA components ≤di to obtain the 4 attributes with the highest squared sum of PCA loadings and list them in a table on the webpage
  - use these four attributes and construct a scatterplot matrix

Task 3: use k-means to find clusters and color the points by cluster ID
  - use the elbow method to find the best k (visualize the function on k)

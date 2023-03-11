# unsupervised-machine-learning-challenge
# Used the provided myopia.csv dataset to:
  # Prepare the data for analysis by removing the MYOPIC column
  # Standardized the dataset to avoid columns with larger values from influencing the outcome over columns with smaller values
# Performed dimensionality reduction with PCA
# Performed further reduction to the dataset dimensions with t-SNE
# Create a scatter plot of the t-SNE output to discover distinct clusters
# Performed cluster analysis with k-means by creating an elbow plot to identify the best number of clusters
# Make a recommendation:
  # Based on the findings from scaling the dataset and performing t-SNE and k-means reduction, these weren't the best models to find clusters
  #because the dataset was too small. Logistics regression is recommended as the best model to split the data, train and test.

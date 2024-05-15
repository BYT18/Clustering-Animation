# K-means Clustering Algorithm

This high school project implements the K-means clustering algorithm in Python. K-means is a popular unsupervised learning algorithm used for clustering data points into K clusters based on their features.

![image](https://github.com/BYT18/Clustering-Animation/assets/68192622/bfef189f-2da5-491c-8a54-dbb283e172a5)


## How it Works

1. **Initialization**: K initial centroids are randomly selected from the data points.
2. **Assignment**: Each data point is assigned to the nearest centroid based on Euclidean distance.
3. **Update**: The centroids are recalculated as the mean of all data points assigned to each cluster.
4. **Repeat**: Steps 2 and 3 are repeated until convergence, i.e., until centroids no longer change.

## Components

- **assignPointsToCentroids**: Function to assign data points to the nearest centroids based on Euclidean distance.
- **recalcCentroids**: Function to recalculate the centroids based on the assigned data points.
- **KMeansND class**: Class encapsulating the K-means algorithm with methods for computing centroids and providing a generator for animation.
- **generateClusters**: Function to generate random clusters of data points.
- **initializeCentroids**: Function to randomly initialize centroids from data points.
- **animate**: Function to draw each frame of the animation showing clustering process.
- **setAxisLimits**: Function to set axis limits for the plot to accommodate data points and centroids.

## Dependencies

- Python 3.x
- NumPy
- Matplotlib

## Usage

1. Run the main script to generate clusters and visualize the K-means clustering process:

```bash
python kmeans.py
```

2. Enter the desired number of clusters when prompted.

3. The script will generate random clusters of data points, perform K-means clustering, and animate the process.

## Results

The animation demonstrates the K-means clustering algorithm in action, showing how centroids move iteratively to optimize cluster assignments.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

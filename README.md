# Cricket Player Performance Analysis

## Objective
The project aims to analyze cricket player performance data using clustering techniques to identify player segments based on their batting statistics.

## Data Preparation
The dataset includes batting statistics of various cricket players. Key attributes considered for analysis include Matches (Mat), Innings (Inns), Not Outs (NO), Runs (Runs), Batting Average (Ave), Balls Faced (BF), and Strike Rate (SR). Initially, the data is standardized using StandardScaler to ensure uniformity in scale across variables.

## Hopkins Statistic
To assess the clustering tendency of the dataset, the Hopkins statistic is computed. This statistic measures the spatial randomness of the data points, with values closer to 1 indicating a high tendency to cluster.

## K-Means Clustering
K-Means clustering is employed to partition the dataset into clusters based on player performance attributes. The number of clusters is arbitrarily set to 4. K-Means iteratively assigns data points to the nearest cluster centroid and updates the centroids until convergence.

## Interpretation
Once clustering is performed, the players are assigned cluster IDs based on their similarity in batting statistics. The clusters can be analyzed to understand different player segments and their respective performance characteristics.

## Visualization
A dendrogram is plotted using hierarchical clustering to visualize the distance between player clusters based on batting strike rate and average. This dendrogram helps identify natural groupings or clusters within the data.

## Outcome
By clustering cricket player performance data, the project aims to uncover distinct player segments based on their batting statistics. This analysis can provide valuable insights for team management, talent identification, and strategic decision-making in cricket.

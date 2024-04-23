# Customer-Segmentation-using-3-clustering-technique

## Summary of EDA and Clustering Analysis
### Summary of Exploratory Data Analysis (EDA)
Distribution Analysis: The distributions of key variables such as age, income, and spending score were explored. Men were found to be slightly older and have higher incomes on average, while women tended to spend more.
Correlation Analysis: Correlation analysis revealed weak relationships between variables, with a particularly weak negative association (-0.33) observed between age and spending score.
Clustering Analysis

### K-Means Clustering
Introduction: K-Means Clustering is a popular method known for its simplicity and effectiveness in segmenting data into distinct clusters.

#### Methodology:

Determining Optimal Number of Clusters (k): The Elbow Method was employed to identify the optimal number of clusters based on the inertia values.
Cluster Visualization: The dataset was partitioned into clusters based on customers' spending score and income. Visual representations of the clusters were provided to facilitate interpretation.
Results: The K-Means model effectively segmented the dataset into five distinct clusters based on customers' spending behavior and income levels.

### Hierarchical Clustering
Introduction: Hierarchical Clustering is an agglomerative clustering approach that progressively merges clusters from the bottom up.

#### Methodology:

##### Dendrogram Analysis: Complete linkage hierarchical clustering was employed, and a dendrogram was generated to visualize the clusters.
Cluster Interpretation: Clusters were interpreted based on customers' spending score and income levels.
Results: Hierarchical clustering identified distinct clusters primarily based on customers' income levels, with varying spending behaviors within each cluster.

### DBSCAN
Introduction: Density-Based Spatial Clustering of Applications with Noise (DBSCAN) is a density-based clustering method capable of identifying irregularly shaped clusters and outliers.

#### Methodology:

Density-Based Clustering: DBSCAN partitions the data based on observation density, distinguishing regions of high density from those of low density.
Outlier Detection: DBSCAN identifies outliers within the dataset, providing insights into data anomalies.
Results: DBSCAN effectively identified clusters of varying densities and pinpointed outliers within the dataset.

### Conclusion
In this analysis, three clustering methodologies were employed to discern various customer profiles within a supermarket: K-Means Clustering, Hierarchical Clustering, and DBSCAN. Each model delineated unique customer segments that could be strategically targeted by the company based on their requirements. Notably, the K-Means model yielded the most distinguishable clusters, whereas DBSCAN produced a simplified model with four clusters and identified outliers within the dataset. Hierarchical Clustering, on the other hand, delineated the fewest clusters overall, with a greater emphasis on customer income.

Drawing insights from customer spending patterns, the company could leverage the K-Means model's two clusters to tailor their membership card program. Customers exhibiting higher spending scores above 60 are likely prime candidates for membership enrollment, especially considering their relatively young age group (under 40). Conversely, customers with lower spending scores could be engaged through targeted marketing campaigns featuring popular products and promotions.

To enhance understanding of customer preferences in the future, additional data on purchase frequency and product preferences could be incorporated. This enriched dataset would enable the company to further personalize product offerings tailored to each customer segment's preferences and behaviors.






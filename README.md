# Clustering Assignment

## Dataset
- Name: Iris Dataset
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php)

## Objective
Perform a comparative performance study of different clustering algorithms using various preprocessing techniques.

## Algorithms
- KMeans
- Agglomerative Clustering
- DBSCAN

## Evaluation Metric
- Silhouette Score


## Results
| **Algorithm**            | **Preprocessing**  | **No. of Clusters** | **Silhouette Score** | 
|--------------------------|--------------------|----------------------|---------------------|
| KMeans                   | StandardScaler     | 3                    | 0.478724               
| Agglomerative Clustering | MinMaxScaler       | 3                    | 0.445540             
| DBSCAN                   | None               | 2                    | 0.349198               

## Conclusion
- KMeans showed the best performance based on silhouette score.
- Preprocessing significantly impacted clustering outcomes.

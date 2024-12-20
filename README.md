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

## Evaluation Metrics
- Silhouette Score
- Adjusted Rand Index (ARI)

## Results
| **Algorithm**         | **Preprocessing**  | **No. of Clusters** | **Silhouette Score** | **ARI** |  
|------------------------|--------------------|----------------------|-----------------------|---------|  
| KMeans                | StandardScaler     | 3                    | 0.55                 | 0.68    |  
| Agglomerative Clustering | MinMaxScaler     | 3                    | 0.52                 | 0.63    |  
| DBSCAN                | None              | -                    | 0.48                 | 0.60    |

## Conclusion
- KMeans showed the best performance based on silhouette score.
- Preprocessing significantly impacted clustering outcomes.

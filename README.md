# MSML651-PySpark-Movie-Recommendation
This repository contains a PySpark-based implementation and analysis 
of collaborative filtering and content-based recommendation algorithms, 
as presented in the accompanying PowerPoint slides.


## Overview

The project explores scalable recommendation system techniques using the 
MovieLens dataset (32M ratings, 200k users, 87k movies). It evaluates 
several algorithms, including baseline models, K-Nearest Neighbors (KNN), 
K-means heuristics, and Alternating Least Squares (ALS) matrix factorization. 
Both prediction accuracy and ranking metrics are analyzed.

## Data

- **Source**: [MovieLens 32M Dataset](https://grouplens.org/datasets/movielens/)
- **Files**: ratings.csv, movies.csv, tags.csv, links.csv
- **Stats**:  
  - 32M ratings  
  - 200,948 users  
  - 87,585 movies  
  - Matrix sparsity: 0.18%

## Files overview

```
.
|   MSML651_Big_Data_Analytics_Mid_Project_Report.pdf      # First draft
|   MSML651_Final_Report.pdf                                                  # Final Report 
|   pyspark-movie-recommendation.ipynb                                  # Analysis and model file
|   README.md                                                                          # Project description
|   Recommendation System using PySpark.pptx                      # Presentation with all information
|   requirements.txt                                                                      # Dependencies
|
+---als_model                                             # Contains parameters for als_model
|   +---bestModel                                         # Best model parameters
```


## Usage

1. Download the MovieLens dataset and place the CSV files in the `ml-32m` directory.
```
\---ml-32m                                                # Store movielens data
        checksums.txt
        links.csv
        movies.csv
        ratings.csv
        README.txt
        tags.csv
```
2. Run the PySpark scripts for each algorithm.
3. Review the PowerPoint slides for detailed methodology, results, and discussion.


## Future Work

- Improve ranking metrics by incorporating content-based and hybrid models.
- Explore advanced neural architectures and temporal modeling.
- Address cold-start and long-tail recommendation challenges.


## References

- [MovieLens Dataset](https://grouplens.org/datasets/movielens/)
- [Recommender Systems The Textbook by Charu C. Aggarwal](https://link.springer.com/book/10.1007/978-3-319-29659-3)
- [ALS in PySpark](https://medium.com/@brunoborges_38708/recommender-system-using-als-in-pyspark-10329e1d1ee1)
- [KNN and Dimensionality Reduction](https://www.youtube.com/watch?v=UPAnUE_g5SQ)
- [Evaluation Metrics](https://w3nhao.github.io/2023/03/31/HR-MRR-NDCG-Torchmetric-Implementation/)
- [Long tail in recommender systems](https://neptune.ai/blog/recommender-systems-metrics)

--- 

**Author:** Peeyush Dyavarashetty  
**Contact:** [peeyu704@gmail.com]

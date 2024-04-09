# Spotify-Clustering

## Overview
1. Clustering the 35,877 pieces of music on the Spotify.
2. Dataset can be download here: ：https://www.kaggle.com/datasets/mrmorj/dataset-of-songs-in-spotify
3. Our paper here: https://github.com/Chia-Wei-Wu/Spotify-Clustering/blob/main/docs/paper.pdf 

## Details
1. We identify the range and significance of each audio feature, while also observing for any missing values or noise.
2. We implement data preprocessing, including data cleaning, feature normalization, addressing imbalance problems.
3. Evaluation different clustering algorithm.

|Case|# Groups|Rand INdex|Normalized Mutual Information|V-measure|
|-|-|-|-|-|
|K-means|3|0.68|0.27|0.27|
|Hierarchical Clustering|3|0.66|0.22|0.22|
|DBSCAN|10|0.44|1.65|1.65|
|GMM clustering|13|0.83|0.17|0.17|
|birch clustering|3|0.55|0.08|0.08|

4. Besides, we use seaborn to select the important features.
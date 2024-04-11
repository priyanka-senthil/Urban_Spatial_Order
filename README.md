# Project Name: Urban Spatial Order Analysis

## Objective:
The objective of this project is to implement clustering techniques on real-world datasets to analyze urban spatial order.

## Background:
The project is inspired by the paper titled "Urban Spatial Order: Street Network Orientation, Configuration, and Entropy" by Geoff Boeing. This paper explores street network patterns across 100 global cities using OpenStreetMap data and OSMnx software. It focuses on metrics such as street orientations, configurations, entropy, average street segment length, circuity, node degree, and proportions of intersections and dead-ends. The research provides valuable insights into urban design and planning, highlighting the complexity and patterns of urban transportation systems worldwide.

## Data:
The dataset used in this project is sourced from the research paper and is available at: [Dataset Link](https://appliednetsci.springeropen.com/articles/10.1007/s41109-019-0189-1)
We will be utilizing Table 1 from the dataset for our analysis.

## Tasks:
1. Having read the research paper and understood the methodology, the urban navigation dataset (Table 1) was loaded.
2. The data was preprocessed, including normalization and scaling of features.
3. K-means clustering was implemented to categorize the data into clusters.
4. The elbow method was utilized to determine the optimal number of clusters.
5. Hierarchical clustering was implemented using an appropriate linkage method.
6. Different linkage criteria were experimented with, and dendrograms were plotted for each.
7. The clustering solution was generated, and the clusters were analyzed to gain insights into urban spatial order.

## Conclusion:
By implementing clustering techniques on real-world urban navigation datasets, we aim to gain valuable insights into urban spatial order, which can inform urban design and planning decisions.


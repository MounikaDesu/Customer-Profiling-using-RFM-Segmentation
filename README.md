# Customer-Profiling-using-RFM-Segmentation

This project focuses on performing customer segmentation analysis for an FMCG store. The primary objective is to create clusters or groups of customers to inform marketing strategies and enhance understanding of customer characteristics, ultimately impacting sales and profit generation.

## Table of Contents

<ul>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#about-the-project">About the Project</a></li>
    <li><a href="#data-gathering">Data Gathering</a></li>
    <li><a href="#file-description">File Description</a></li>
</ul>


## Installation

To run the code, you need the following:

<ul>
    <li>⁠Python 3 and above</li>
    <li>pandas</li>
    <li>sklearn</li>
    <li>⁠PowerBI Desktop (for visualization purposes)</li>
</ul>


## About the Project

Clustering analysis is a key aspect of unsupervised machine learning, aimed at grouping features into clusters for further exploration. As Yann LeCun aptly put it, “if intelligence was a cake, unsupervised learning would be the cake, supervised learning would be the icing on the cake, and reinforcement learning would be the cherry on the cake”. This highlights the significant potential of unsupervised clustering algorithms.

In the realm of business intelligence, creating groups of customers or product consumers is often valuable for various purposes, such as marketing, recommendation systems, or data analysis. Cluster analysis has proven to be highly effective in meeting business needs for customer segmentation.

In this project, we applied the K-means clustering algorithm to a dataset containing 2000 instances. We created 4 distinct customer segments based on 7 features. The K-means algorithm is a popular choice for clustering models due to its intuitive and straightforward approach. After forming these segments, we developed an interactive dashboard to analyze the differences among the customer segments based on the gathered features. For instance, we examined how the average income of one customer segment compares to another. PowerBI's interactive features, including slicers, facilitated this analysis.

## Data Gathering

The data was sourced from Kaggle's extensive repository of datasets.

## File Description

The folder contains the following:

- ⁠⁠Datasets ⁠: This folder contains the original dataset and the dataset generated after creating the clustering model, which served as an input for the PowerBI dashboard.
- customer.ipynb ⁠: A Jupyter notebook detailing the creation of the clustering model.
- Customer Segmentation.pbix ⁠: The PowerBI dashboard created from the analysis. This file should be opened with PowerBI Desktop.

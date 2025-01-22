# CryptoClustering

This repository demonstrates how to cluster cryptocurrencies based on their price change percentages using the K-means clustering algorithm. The goal is to identify the optimal number of clusters (`k`) for the K-means algorithm using the elbow method and then apply K-means to group the cryptocurrencies.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Prerequisites](#prerequisites)
3. [Steps](#steps)
   - [Find the Best Value for k Using the Elbow Method](#find-the-best-value-for-k-using-the-elbow-method)
   - [Cluster Cryptocurrencies Using K-means](#cluster-cryptocurrencies-using-k-means)
4. [Example Code](#example-code)
5. [Visualizations](#visualizations)
6. [Contributing](#contributing)
7. [License](#license)

## Project Overview

In this project, we apply the K-means clustering algorithm to group cryptocurrencies based on their price change percentages over 24 hours and 7 days. The process is as follows:
1. Use the elbow method to determine the optimal number of clusters (`k`).
2. Apply K-means clustering with the optimal `k` to segment the cryptocurrencies.
3. Visualize the clusters on a scatter plot to better understand the distribution of cryptocurrencies.

## Prerequisites

Before running the code, ensure you have the following Python libraries installed:

- `pandas` (for data manipulation)
- `matplotlib` (for plotting)
- `scikit-learn` (for K-means clustering)
- `hvplot` (for interactive plotting)

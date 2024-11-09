# Network Analytics Project
#### This project performs Network Analytics on a dataset of flight routes using Python libraries like Pandas and NetworkX. It explores various centrality measures to understand the importance of nodes (airports) in the network.

## Table of Contents
#### Introduction
#### Features
#### Dataset
#### Installation
#### Usage
#### Results

## Introduction
####  Network Analytics helps in understanding the structure and dynamics of complex networks. This project focuses on analyzing flight routes to identify key airports using centrality measures like Degree Centrality, Closeness Centrality, Betweenness Centrality, and Eigenvector Centrality.

## Features
#### Load dataset and create a graph from flight routes.
#### Calculate various centrality measures to analyze the network.
#### Visualize the network graph using networkx.
#### Compute clustering coefficients to understand the network's clustering properties.

## Dataset
#### The dataset (routes.csv) contains information about flight routes between various airports.
#### Columns of interest include:
#### Source Airport
#### Destination Airport
#### The project uses only the first 500 rows and columns from index 1 to 9 for analysis.

## Installation
#### Prerequisites
#### Python 3.7 or above
#### Required Python packages:
#### pandas
#### networkx
#### matplotlib
#### decorator==5.0.7 (to avoid compatibility issues)

## Install the required packages
#### pip install pandas networkx matplotlib decorator==5.0.7

## Results
#### Degree Centrality: Indicates the number of direct connections each node (airport) has.
#### Closeness Centrality: Measures how close a node is to all other nodes in the network.
#### Betweenness Centrality: Represents the frequency at which a node appears on the shortest paths between other nodes.
#### Eigenvector Centrality: Highlights the influence of nodes based on their connections.
#### Clustering Coefficient: Shows the extent to which nodes cluster together.

# Waste Collection Optimization Project

This repository contains notebooks for optimizing waste collection routes using the K-means clustering method. The project involves clustering customer data to determine collection points and building an optimized route for waste collection. The repository is organized into four notebooks:

1. **Clustering**: This notebook performs K-means clustering on customer data to identify optimal collection points.
2. **Allocation to Feasible Locations**: This notebook allocates the clustered collection points to feasible locations for waste collection.
3. **Routing**: This notebook builds an optimized route for waste collection based on the allocated collection points.
4. **Route Visualization**: This notebook visualizes the optimized route for better understanding and analysis.

## Notebooks

1. **Clustering**: `clustering.ipynb`
   - Uses K-means clustering to analyze customer data.
   - Identifies and visualizes optimal collection points.

2. **Allocation to Feasible Locations**: `allocation.ipynb`
   - Allocates collection points to feasible locations.
   - Ensures practical and accessible points for waste collection.

3. **Routing**: `routing.ipynb`
   - Develops an optimized route for waste collection.
   - Uses routing algorithms to minimize travel time and distance.

4. **Route Visualization**: `route_visualization.ipynb`
   - Visualizes the optimized waste collection route.
   - Provides a graphical representation of the route for analysis.


## Prerequisites

Ensure you have the following Python libraries installed:
- numpy
- pandas
- scikit-learn
- matplotlib
- folium
- ortools

You can install these libraries using:
```sh
pip install numpy pandas scikit-learn matplotlib folium ortools
```

# Cover Time of Simple Random Walks on a Graph

**Course:** Probability for Data Science (Master’s Degree)  
**Project:** Investigating cover times of simple random walks on complete graphs

## Overview  
This project studies the **cover time:** the expected number of steps needed for a random walk to visit all vertices on a graph. Specifically, it analyzes how running multiple independent random walks in parallel speeds up coverage on complete graphs.

## Objectives  
- Show that the cover time T_cov(G) on a complete graph of size n grows as c * n log n.  
- Demonstrate that the k-cover time T_k_cov(G) with k = n grows approximately as c * log n.  
- Perform simulations for graph sizes n = 500^alpha, with alpha = 1, ..., 20.

## Method  
- Simulate single and parallel random walks on complete graphs.  
- Estimate expected cover times through repeated simulations.  
- Analyze and plot growth trends.

## Usage  
- Run the main script to reproduce simulations and plots.  
- Requires Python with standard scientific libraries (numpy, matplotlib, etc.).

# high-throughput-assignment-5
Author : Bhavana Parupalli
Date:04/27/2024
programming language:Python(3.8) 
#Dependencies:-
pandas
matplotlib
network
scipy.stats
numpy
ranksums
The first script, network_analysis.py, analyzes network structure by loading protein interaction data and forming a graph. It calculates each protein's degree, indicating its connectivity, and determines the clustering coefficient, which assesses the tendency of protein clusters to form. It also computes the average clustering coefficient for the network and visualizes the network's degree distribution on a log-log scale. This helps identify scale-free characteristics, crucial for understanding network dynamics.

The second script, path_analysis.py, focuses on the shortest paths within the PPI network for specific protein subsets, critical for analysis functional pathways. It calculates the shortest path lengths between protein pairs in each subset and employs a Wilcoxon rank-sum test to statistically compare path length distributions between two protein groups. This analysis highlights potential differences in their biological functions or roles.
 files:- protein-list1.txt ,protein-list2.txt files, Human-PPI.txt file.

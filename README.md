# HCD
The folder contains the following three data files and our R code for the paper "Hierarchical community detection by recursive partitioning".

1. The R data file with the adjacency matrix with row names being author names. It is 707 by 707. It is the pruned core with all nodes have at least three connections, extracted from the largest connected component of the original network

2. The full list of authors, their degrees and the cluster label from our algorithm

3. The top 20 authors (by degree) from each community (if the community have more than 20 authors) and their research interests from internet

Please refer the following two papers if the data are used.

1. The citation network was originally from collected in
Coauthorship and citation networks for statisticians.
Ji, Pengsheng, and Jiashun Jin. 
The Annals of Applied Statistics 10, no. 4 (2016): 1779-1812.

2. The community label and research interests information are added by our analysis in the paper
Hierarchical community detection by recursive partitioning
Tianxi Li, Lihua Lei, Sharmodeep Bhattacharyya, Purnamrita Sarkar, Peter J. Bickel, Elizaveta Levina
https://arxiv.org/abs/1810.01509

# HCD
The folder contains the following three data files and our R code for the paper "Hierarchical community detection by recursive partitioning".

1. Citation3Core.Rda: The R data file with the adjacency matrix with row names being author names. It is 707 by 707. It is the pruned core with all nodes have at least three connections, extracted from the largest connected component of the original network

2. ECV-FullAuthorCommunity.csv: The full list of authors, their degrees and the cluster label from our algorithm

3. ECV-Truncated20AuthorCommunity.csv: The top 20 authors (by degree) from each community (if the community have more than 20 authors) and their research interests from internet

4. PaperCodeOnline.zip: the original code for the paper simulation. Notice that the code is not polished and contains many unused options. We include it here for transparency but generally recommend anyone who are interested to use the clean version of our code -- the R package HCD (see next).

5. HCD_0.1.tar.gz: the R package HCD for our algorithm. It is a CRAN compatible version and can be directly installed in R by using install.packages. The package is also available on CRAN.

Please refer the following two papers if the data are used.

1. The citation network was originally from collected in
Coauthorship and citation networks for statisticians.
Ji, Pengsheng, and Jiashun Jin. 
The Annals of Applied Statistics 10, no. 4 (2016): 1779-1812.

2. The community label and research interests information are added by our analysis in the paper
Hierarchical community detection by recursive partitioning
Tianxi Li, Lihua Lei, Sharmodeep Bhattacharyya, Purnamrita Sarkar, Peter J. Bickel, Elizaveta Levina
https://arxiv.org/abs/1810.01509

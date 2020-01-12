# PageRank algorithm to rank academic journals in a network of journals

###### links.txt - journal-citation file
###### PS2_IMT574_Spring2019 - Documentation for PageRank
###### srinivas_ashwin_PS2.ipynb - Jupyter Notebook file with the analysis

This project contains the implementation of PageRank algorithm to rank academic journals in a network of journals to determine the top "most influential" journals.
The journals are ranked on the basis of their importance in the journal-citation file (links.txt)


This project has the following parts:


Part 1 - Import and format the journal-citation matrix

Part 2 - Initialize and populate the adjacency matrix

Part 3 - Removing self-references

Part 4 - Normalize adjacency matrix column-wise to get the share of each publisher

Part 5 - Compute the dangling-node vector. This will be the column sums of the normalized matrix

Part 6 - Initialize the article vector and influence vector (for the first iteration)

Part 7 - Implement PageRank formula

Part 8 - Calculate Eigenfactor 

Part 9 - Retrieve scores for top 20 most influential journals

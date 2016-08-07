A python implementation to calculate the Avergae-F1 score of two given networks partitioning into communities, 
as presented in "Overlapping community detection at scale: a nonnegative matrix factorization approach".

Input is two files containing lists of nodes, and a path to the output file. Each line describes a community.
Nodes are space delimited.
	Example:
	1 2 3 4
	2 3 4

Use the AverageF1 method. 
In case you have a ground-truth partitioning to compare to, place it as the second parameter. 
	
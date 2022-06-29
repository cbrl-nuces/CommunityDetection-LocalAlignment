***************** Community Detection and Local PPI Network Alignment *******************

Inputs Required:
PPI networks
Uniques nodes/proteins of both networks
Expression data for both network's proteins (missing protein expression data can be filled with zero-vector)

Steps:
1) Open jupyter notebbok
2) Execute the file "GraphSAGE.ipynb" to get embeddings of both networks.
3) Execute the file "Agglomerative_clustering_Mouse.ipynb" to get cluters of the Mouse networks.
4) Execute the file "Agglomerative_clustering_Human.ipynb" to get cluters of the Human networks.
5) Execute the file "Communities_local_alignment.ipynb" to get communities alignment (local alignment).

The code files contains comment section for re-producing the results. Please read the comments carefully.
Note: Carefully update the file_paths given in the code

In case of any query, feel free to contact us.
Contact: umair.ayub@nu.edu.pk
Contact: hammad.naveed@nu.edu.pk

# Project-Graphs
Analysis of Paris Metro System 

##Introduction
Data 1 : Gares et stations trouvable to know the names of the stations.

Data 2 : Tracé des lignes to know the link between the stations.

Data 3 : Traffic entrant des stations to know the real importance of the stations.

Data 4 : Couleur des lignes de métro to draw the lines with the official colours.

We retrieved a document containing the station data.

In the following document, it's possible to find information about the Metro System of the city of Paris. Focusing only on the metro stations and the connection between them, a potentially connected graph is going to be formed, representing the city's interconnection between the metro lines. With the extra information provided in the documents attached, we have the possibility to do a detailed analyze of the graph.

From the documents attached, we were able to take the information needed, which are the nodes, representing the stations of each metro. The connection between them is specified in the second document, making it possible to create a potentially connected undirected tree. Each connection is going to have a weight attached to it, representing a good approximation distance between two stations. The detailed Geo Shape information provided in the documents permits to take into consideration the real position of the station, in order to have a specific representation of the nodes in the graph.

Filter: only the data of the points found in document 1 are used

Link: the minimum distance between a point in DOC2 and one of the points on the DOC1 lines is calculated.
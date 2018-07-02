# Pagerank
learning to use the Pagerank algorithm.

[Basic PageRank:](https://nbviewer.jupyter.org/github/TarunSunkaraneni/Pagerank/blob/master/python/matrix_pagerank.ipynb) This notebook goes over specifics of implementing PageRank with teleportation. Even though teleportation isn't a basic concept to implement with the basic idea Pagerank presents, the algorithm is able to gauge importance of a page much better when given ability to teleport.

[PageRank Variations:](https://nbviewer.jupyter.org/github/TarunSunkaraneni/Pagerank/blob/master/python/pagerank_variants.ipynb) This notebook goes over the different tricks which PageRank algorithm uses to make its usage more versatile. Specifically two tricks covered ensure that the graph created by the input matrix forms an ergodic graph, and that is achieved by handling two different problems of ***Spider traps*** and ***Dead ends***. To combat them, we make sure our graph is irreducible (by teleportation), and Stochastic (to handle _complete_ and _leaky_ dead-ends).

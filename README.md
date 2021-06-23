# Shortest-Path-Routing

In this project, we evaluate the ease of graphs to get congested in time by assigning all demands to the shortest paths, where it is mainly a challenge and also a good metric to compare road networks. In this context, we handle a real world road network as G1, which represents the road network of Quebec, Canada [Jaballah et al. 2019]. Considering the nature of real world road networks where there are many nodes which can represent attraction points or intersections with degrees (2-3, 4 at most), as the second graph, G2, we consider a scale free graph in which there are nearly same number of edges as G1 but considerable less nodes. The general topology of scale free graphs that brings heterogenity to the network where majority of node has low degree (1-2), except few nodes that ensures connectivity within networks [Albert et al. 2000], enables us to compare how the metrics that we've concantrated will change if we design road networks by aggreagating some nodes together instead of having many nodes with low degrees.

Please note that this work is done as an assignment of Graph Theory course (https://www.youtube.com/playlist?list=PLug43ldmRSo3MV-Jgjr30E5SpwNKkjTvJ) Fall 2020, in Istanbul Technical University.


References

Albert R., Jeong H., Barabasi A., 2000, Error and attack tolerance of complex networks, Nature, vol. 406, pp. 378-382.

Jaballah R., Veenstra M., Coelho L.C., Renaud J., 2019, The time dependent shortest path and vehicle routing problem, CIRRELT-2019-12.

# Convex_Optimization

This notebook uses CVXPY to economically optimize a small 13 node power system. 

Parameters for the system model are created in Part 2 of the notebook.  Active and reactive power consumption is set at each node, and apparent power con-sumption is calculated from these values for each node.  Maximum generating power and marginal cost for each node is also set for each node.  The minimal and maximal node voltages or also set, with a 5% band around 1.00 p.u, where the minimum is 0.95 p.u.and the maximum is 1.05 p.u.. Network data includes the resistance and reactance between nodes, as well as the maximum line current.  In these sections, values are only placed where there is a connection, as per the adjacency matrix. Zero values indicate no connection. The network data also includes a list of node indices and the list ofparent nodes, ρ(j).

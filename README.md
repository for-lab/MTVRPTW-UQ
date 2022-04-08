MTVRPTW-UQ

This repository contains the instances and results used in our paper "Multi-Trip Vehicle Routing Problem with Time Windows and Unloading Queue".

This paper introduces a new vehicle routing problem that simultaneously considers multiple trips, time windows, and an unloading queue at the depot. This problem is a generalization of the multi-trip vehicle routing problem with time windows, which determines a set of least-cost vehicle routes to fulfill all customer demands while respecting the constraints of vehicle capacity and time windows. Due to restricted resources (e.g., equipment and labor force) at the depot, vehicles may need to wait in a queue for being unloaded when they arrive. This unloading capacity constraint significantly complicates the problem, as it causes a trip to involve three stages---traveling, waiting, and unloading. 

Instances

Instances includes all instances used in our paper. Our experiments were performed using instances based on the well-known VRPTW benchmark instances created by Solomon(1987). For all the instances, we let vehicle capacity Q=100. The unit unloading time is set to 1 for type C2 instances and 0.2 for types R2 and RC2 instances. We generate 189 instances, where the number of customers takes values from set {25, 35, 40, 50, 70, 80, 100 } and the corresponding fleet size takes values from set {2, 3, 4, 4, 6, 6, 8}. The unloading capacity C is set to 1, 1, 2, 2, 3, 3, and 4, respectively.
To analyze the impact of unloading capacity C, our experiments are conducted on instances with 50 customers. We set the unit unloading time to 2 for type C2 instances and 1 for types R2 and RC2 instances. We vary the value of C from 1 to 3.

Results

Results includes all results from two solution methods, i.e., CPLEX for solving arc flow model directly and a branch-and-price-cut(BPC) exact method. Table "CPLEX" represents the results obtained by solving arc flow model directly. Table "BPC" represents the results obtained by BPC exact method. Table "Impact of Unloading Capacity" represents the results obtained by BPC exact method to analyze the impact of unloading capacity C.

Contact Info

Feel free to contact us for more information about our paper via email:
Nan Huang (nan_huang@hotmail.com),
Chun Cheng (chun.cheng@polymtl.ca).


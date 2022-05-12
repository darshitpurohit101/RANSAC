# RANSAC
Implemented the Sequential RANSAC (SeqRANSAC) algorithm with optimal plane detection to find the three most dominant planes by SeqRANSAC. Experimented with the RANSAC parameters to find good planes. 

Run the program on all the data given in this ZIP file. 

 Sequential RANSAC is the iterative modification of RANSAC: it finds a plane by RANSAC, then the plane points are removed from the dataset, and RANSAC method is run again on the rest of the points. The plane detection and removal can be iterated many times. 

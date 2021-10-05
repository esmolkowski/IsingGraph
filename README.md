# IsingGraph
#### June 2021
A basic monte carlo ising model simulation in an arbitrary lattice pattern.  
  
Original 2d lattice verion by Eric Corwin, University of Oregon.  
Remade by Elyse Smolkowski to become structure and dimension agnostic by using graphs.  
  
This program provides a basic monte carlo ising model simulation in an arbitrary lattice pattern in any dimension. Included are several constructors to create 2d,3d, and 4d square lattice patterns, but theoretically any structure is possible. One caveat of the way this script is programmed is that it does not account for the distance between neighbors. This could lead to issues in structures with unequal distance between neighbors. At some point in the future I would like to account for this, add better visualizations, and remake the script in C++.

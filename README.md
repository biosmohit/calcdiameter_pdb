# calcdiameter_pdb
Calculate Diameter of PDB file using Python

It is a method to find the maximum diameter of a ring-shaped protein complex of symmetry Coordinate. It returns the maximum distance between the num top and num bottom points.
The maximum distance between any pair of points that are within bin Angstrom of one another. Along the Z axis as well as the x,y coordinates of each point and the corresponding residue labels and the radius
Thefinddiameter function is the main function that finds the best orientation such the structure that it lies flat on the XY planeand then returns the maximum diameter in a given data.

The calcdiameter function that reads the pdb  file  and invokes the findDiameter function You can set the tolerated heigt difference between points using the bin_ parameter (default=3 Angstrom).
You can set no rotation to True if you believe that the pdb is already correctly oriented - the structure is already flat on the XY plane
You can inspect the initial and final orientations of the structure in 3d by setting plot3d to True. First you will see the initial orientation of the pdb
from all angles, then close it to see the best orientation that the program has found  the structure should lie flat on the XY plane close the plot to obtain the max diameter
    
By default, plot=True the projection of all CA atom coordinates on the XY plane is plotted.The title of the plot specifies the max diameter in Angstroms and provides the labels for the tworesidues.
The diameters of PDBs that have rotational symmetry Cn and specified minimum (0.0) and maximum resolution (3.0).




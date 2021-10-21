For each test case a .mat file is provided that contains one matlab structure.
In each structure there are all the necessary data to reproduce the optimized structures and see the section property of each frame.
The matrix [nodes] has the xy coordinates of the nodes.
The matrix [connec] has the connectivity of the frame structures, the indexes of the nodes that are connected.
The vector [L_total] has the length of each frame, while the vectors [L_col], [L_beam] and [L_diag] have the same information but separated for the columns, beams and braces respectively.
From the size of each of the last vectors the number of the columns, beams and braces is derived.
Finally the matrix [a] contains the area of each frame (in the first column), while in the second column the index of the section property according to the table 5 in Appendix is provided.
Important to notice that in order to fulfill the [connec], [L_total] and [a] matrices, we wrote first the columns, then the beams and then the braces.
In this way the reader can identify which section property is assigned to every frame.
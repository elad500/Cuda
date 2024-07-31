The project contains square matrices of integers with N rows and cols, which deals with sets of pictures and objects of different sizes
each member of the matrix represents color range[1,100].
Position(I,J) defines coordinates of the upper left corner of the object into picture.
for each pair of overlapping members p and o of the Picture and Object we will calculate a relative different
different = abs((p-o)/p)
The total difference is difined as an average of all relative differences for all overlapping members for given postion(i,j) of 
the object into picture. we will call it Matching(I,J).
The project finds if the given picture contains at least three objects from the given object set (using cuda and openmp and mpi)

# Levenshtein-distance
calculating Levenshtein distance using python
==================================================================================================================
pass the two words a and b


step 1 :
==================================================================================================================
create metrics of the of length a+1 and breadth b+1                              

step 2


initialise the the first row of the metrics with incremental numbers from 0 to len(a) + 1
initialise the the first column of the metrics with incremental numbers from 0 to len(b) + 1

******************************************************************************************************************

step 3 :
==================================================================================================================

once you initialise the first column and first row, then fill the rest of the metrics according to below conditions,

if x == y that is where x is char in a and y is a char in b
then we will pass diagnol element of the previous row
if x != y then we will pass
min of the 
(lengths[i][j+1], lengths[i+1][j], lengths[i][j])

we will return the last element that is right corner element

******************************************************************************************************************

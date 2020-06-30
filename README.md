Description : Given a coordinates of buildings and source point 'p' of sunlight. Calculate the length of building exposed to sunlight having the source at point p.




Write a function that takes two arguments as a input and return length of the building exposed to sunlight
Input 1 : $(n42)$ array consisting the coordinates of n buildings in 2-D, where n is number of buildings
Input 2 : coordinated of source of light in 2-D
Output : (float) Length of surface exposed to sunlight

Example :

Case 1

Input -
$ Buildings Coordinates$ : $ [[[4,0],[4,-5],[7,-5],[7,0]]] $
$ S $: $ [1,1] $
Output : 8.0

Case 1

input
$ Buildings Coordinates$ : $ [[[4,0],[4,-5],[7,-5],[7,0]], [[0.4,-2],[0.4,-5],[2.5,-5],[2.5,-2]]] $
$ S $: $ [-3.5,1] $
Output : to be calculated

provide->
input1:buildingCoords[size][4][2]
input2:source[2]

call->
requiredLength=getExposedLength(size, buildingCoords, source);


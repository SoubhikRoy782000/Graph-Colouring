# Graph-Colouring

Problem Statement –

To solve Graph colouring problem using greedy approach for vertex colouring (colouring vertices such that no two adjacent vertices share same colour), edge colouring (colouring edges 
such that no two adjacent edges share same colour) and face colouring (colouring each face such that no two adjacent faces share same colour).

Algorithm –

STEP 1 – Colour first vertex with first colour.
STEP 2 – Loop for remaining V-1 vertices.
STEP 3 – Consider the currently picked vertex and colour it with the lowest numbered colour that has not been used on any previously coloured vertices adjacent to it.
STEP 4 – If all previously used colours appear on vertices adjacent to v, assign a new colour to it.
STEP 5 – Repeat the following for all edges. 4. Index of colour used is the chromatic number.

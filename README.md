# PXL_A-star_demo
1. Initialize list for ‘open’ and ‘closed’ nodes
2. Loop through all the nodes and place the node with the lowest f_cost in the openList. 
3. Place node in closedList
4. Find the node with the lowest fCost and place it in the openList
5. Check if the fCost of the current node < fCost of the new node
6. Compare the hCost if the fCost is the same
7. Check if the current node == the target
8. Retrieve the neighbours
9. Check if the neighbours are not walkable or in the closedList
10. Place the neighbour in openList IF the path is shorter or when it’s not in the openList yet
# MASAABA-EVANS-AI-Practical-1
MAZE PROBLEM
Start state; (0,0)
Goal state; (4,4)
Actions; move up, down, left or right adjacent to the cell but do not pass through the wall.

DISPATCH-AMBULANCE
State space: ambulance location (node) represented by coordinates such as A, B, C, D, E, F
Actions: movement of ambulance from current node to connected neighbouring node from node A to either B or C
Goal: to reach a specified destination node which is F
Path cost: time or distance along a choosen path which is 7
Search strategy:   The algorithm uses A* search, which combines the actual cost from the start node and a heuristic estimate to the goal which ensures the shortest and most efficient path since the goal is known. (informed search)

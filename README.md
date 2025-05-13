This project explores and visualizes ego-centric social network graphs using the ego-Facebook dataset from the Stanford Network Analysis Project (SNAP). It focuses on understanding the internal structure of friend-to-friend relationships within individual ego networks and the combined Facebook graph.
🔍 Project Objective
To analyze structural patterns in ego networks using graph theory and visualize key properties such as connectivity, traversal paths, and cycle structures (triangles, quadrilaterals).

📁 Dataset
Source: SNAP Ego-Facebook Dataset
Type: Undirected, unweighted graphs in .edges format
Size:facebook_combined.txt: 4,039 nodes, 88,234 edges
686.edges: 168 nodes, 1,656 edges (sample network for in-depth analysis)

⚙️ Key Features
Load and analyze individual ego networks or the combined graph.
View graph properties (node count, edge count, connectivity).
Visualize BFS and DFS trees using Matplotlib.
Detect simple cycles, triangles, and quadrilaterals.
Export graphs to Gephi (.graphml) for advanced visualization.

🧪 Technologies Used
Python 3
NetworkX
Matplotlib
Gephi (external for .graphml visualization)

🧭 Menu-Driven Interface
The program includes an interactive menu that allows users to:
Load graph files
View adjacency matrices/lists
Check graph connectivity
Run traversal algorithms (BFS/DFS)
Detect cycles
Export to Gephi

📊 Sample Results
facebook_combined.txt:
84,196 simple cycles
1,612,010 triangles
4,607 quadrilaterals

686.edges:
1,489 simple cycles
7,945 triangles
157 quadrilaterals

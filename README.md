TEST SCRIPT IS script.py which can be customised with your own custom cases writing inside the script and tested with python3 scrip.py and can also be tested differently which is commented in the last of the file



Implemented a robust graph data structure in Python. Our two classes, Vertex and Graph are capable of representing the typical variations in graphs that occur in many different algorithms.

Vertex:

    Uses a dictionary as an adjacency list to store connected vertices.
    Connected vertex names are keys and the edge weights are values.
    Has methods to add edges and return a list of connected vertices.


Graph:

    Can be initialized as a directed graph, where edges are set in one direction.
    Stores every vertex inside a dictionary
    Vertex data is the key and the vertex instance is the value.
    Has methods to add vertices, edges between vertices, and determine if a path exists between two vertices.



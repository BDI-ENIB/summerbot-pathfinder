## Small Scale PathFinder Lib
Based on a dijkstra algorithm
# usage
~~~~ PathFinder pf;
PathFinderNode node1* new PathFinderNode(0,0)\
PathFinderNode node2* new PathFinderNode(10,10)\
node1->addLink(node2);\
pf.addNode(node1);\
pf.addNode(node2);\
pf.findPath(node1,node2);\
pf.findPath(node1,node2);\
~~~~

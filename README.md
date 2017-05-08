# Final Exam Review
For Professor Scott Johnson
By: Tim Zabel

## class types and inheritance

### encapsulation
hides from the outside world

### 

## Java Collections Framework

### Maps
Need 'equals()' function

#### CompareTo function
Needs to return an int

#### Difference between list and maps
maps use any object, but must be hashed, and include equals() method.

#### TreeMap
Keeps in sorted order, does not allow duplicates in values

### Sets

#### TreeSet
Keeps sorted, no duplicates

### Iterable Interface
Allows forEach method

Anything that is able to be iterated through uses this indirectly

## Graph Searching

### Breadth First Search
Uses stacks

### Depth First Search
Uses queues

#### BFS and DFS do not always return shortest path

#### Predecessor Map
Already visited nodes, and allows for the actual path to be returned when algorithm finishes

### Directed vs Undirected Graphs
<ul>
<li>In directed, you can only traverse one way, limits the path</li>
<li>With undirected, paths go either way</li>
</ul>

## Backtracking
<ul>
<li>Gives two configurations using getSuccessors()</li>
<li>isValid() checks to find the valid configuration of the two</li>
<li>Valid configuration then updates the internal state</li>

### Pruning
<ul>
<li>Makes algorithm time much shorter</li>
<li>Prunes off bad paths</li>
</ul>
















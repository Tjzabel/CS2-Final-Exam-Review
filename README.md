# Final Exam Review
* For Professor Scott Johnson
* By: Tim Zabel

## class types and inheritance

### encapsulation
* hides from the outside world

### 

## Java Collections Framework

### Maps
* Need 'equals()' function

#### CompareTo function
* Needs to return an int

#### Difference between list and maps
* maps use any object, but must be hashed, and include equals() method.

#### TreeMap
* Keeps in sorted order, does not allow duplicates in values

### Sets

#### TreeSet
* Keeps sorted, no duplicates

### Iterable Interface
* Allows forEach method
* Anything that is able to be iterated through uses this indirectly

## Graph Searching

### Breadth First Search
* Uses stacks

### Depth First Search
* Uses queues

#### BFS and DFS do not always return shortest path

### Predecessor Map
* Already visited nodes, and allows for the actual path to be returned when algorithm finishes

### Directed vs Undirected Graphs
* In directed, you can only traverse one way, limits the path
* With undirected, paths go either way

## Backtracking
* Gives two configurations using getSuccessors()
* isValid() checks to find the valid configuration of the two
* Valid configuration then updates the internal state

### Pruning
* Makes algorithm time much shorter
* Prunes off bad paths

## Exceptions

### Checks vs. Unchecked
* In checked, we can check them in advance
* Unchecked exceptions you cannot look for

### _A program cannot continue after an exception_

* try-catch blocks are used in order to use exceptions

## Threads
* Wait() and NotifyAll()
* Synchronized 
* Sleep() makes a thread sleep for a certain amount of time
* Yield()
* Run() method
* Start() calls run

#### Ways to Make a Thread
* Extend Thread
* Implement Runnable

#### Process vs. Threads
* Processes cannot share memory
* Processes are made up of many threads
* Threads can share memory
* Threads are used to do multiple tasks at the same time


## IO
* Used to read and write input and output

### Streams
* Input streams
* Output streams

#### _Classes must implement Serializable in order to be written to a file_

## Networking
* Understand TCP and UDP
*** TCP needs a connection
*** UDP sends out information, does not need a client/server interaction





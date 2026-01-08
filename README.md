# MLA0102-AI-G-Vishnu-Madhav

##  1. DEPTH FIRST SEARCH (DFS) – Algorithm

1. Start
2. Create an empty list called **Visited**
3. Push the **starting node** into a **stack**
4. While the stack is not empty:

   * Pop a node from the stack
   * If the node is not in Visited:

     * Print the node
     * Add the node to Visited
     * Push all unvisited adjacent nodes into the stack
5. Stop

---

##  2. BREADTH FIRST SEARCH (BFS) – Algorithm

1. Start
2. Create an empty list called **Visited**
3. Insert the **starting node** into a **queue**
4. While the queue is not empty:

   * Remove a node from the front of the queue
   * If the node is not in Visited:

     * Print the node
     * Add the node to Visited
     * Insert all unvisited adjacent nodes into the queue
5. Stop

---

## 3. UNIFORM COST SEARCH (UCS) – Algorithm

1. Start
2. Create an empty list called **Visited**
3. Insert the start node with cost **0** into a **priority queue**
4. While the priority queue is not empty:

   * Remove the node with the **lowest path cost**
   * If the node is not visited:

     * Print the node
     * Add the node to Visited
     * If the node is the goal, stop
     * Insert all neighboring nodes with updated cost into the queue
5. Stop

---

##  4. WATER JUG PROBLEM – Algorithm

1. Start
2. Define the capacities of **Jug 1** and **Jug 2**
3. Set the initial state as **(0, 0)**
4. Set the goal state
5. Use a queue to store the states
6. While the queue is not empty:

   * Remove a state from the queue
   * If the state is the goal, stop
   * Generate all possible next states:

     * Fill Jug 1
     * Fill Jug 2
     * Empty Jug 1
     * Empty Jug 2
     * Pour water from Jug 1 to Jug 2
     * Pour water from Jug 2 to Jug 1
   * Add unvisited states to the queue
7. Stop

---



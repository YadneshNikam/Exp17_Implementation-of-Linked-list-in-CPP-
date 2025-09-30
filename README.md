# Exp17_Implementation-of-Linked-list-in-CPP-
### Aim  
To implement the linked list data structure in C++.

### Software Required  
- VS Code   
### Program 1  
#### Theory and Explanation  
This program introduces the basics of a linked list by creating a `Node` class in C++. Each node contains an integer value and a pointer to the next node, forming the foundation for pointer-based connectivity. Two nodes are dynamically allocated and linked to create a chain, and a `display()` method outputs their contents and linkage status. This example emphasizes memory allocation and object-oriented concepts—ideal for beginners learning dynamic data structures.

#### Algorithm  
- Define a `Node` class with data and next fields  
- Dynamically allocate two nodes  
- Link the first node to the second  
- Display each node’s data and linkage using `display()`  
- End  

### Program 2  
#### Theory and Explanation  
Here, a singly linked list is implemented with dynamic memory allocation and head insertion functionality. The `Node` class holds data and a pointer to the next node. The `addToFront()` function inserts new nodes at the beginning by updating the head pointer, and the `printList()` function traverses the list, printing node values and signaling the end with NULL. This structure supports efficient O(1) insertions, making it suitable for stack-like operations and reinforcing concepts of pointer manipulation, memory management, and traversing in OOP style.[3][4][1]

#### Algorithm  
- Define a `Node` class with data and next fields  
- Initialize head to nullptr  
- For each value:  
  - Create a new node  
  - Point its next to the current head  
  - Update head to the new node  
- Traverse and print the list with `printList()`  
- End  

### Conclusion  
Both programs demonstrate the fundamental principles of singly linked lists in C++, including dynamic memory management, pointer-based node linking, and modular function design. Whether using a simple two-node chain or repeatedly inserting at the head, these samples illustrate how data structures can be constructed, manipulated, and traversed efficiently. Using OOP practices like encapsulation in the node class and reusable methods such as `display()` and `insert_head()` provides a solid foundation for advanced operations such as deletion, tail insertion, or full encapsulation in further object-oriented designs

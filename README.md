# Data Structures And Algorithms
----
 ## Table of Contents
 * [Data Structure](#data-structure)
 * [Array](#arraypractice)
 * [Linkedlist](#linked-listpractice)
 * [Stack](#stackpractice)
-----
## Data structure

Data structure is a particular way of storing and organizing data in a computer so that it can be used efficiently.

General data structure types include arrays, files, linked lists, stacks, queues, trees, graphs and so on.

Depending on the organization of the elements, data structures are classified into two types:

![](https://media.geeksforgeeks.org/wp-content/uploads/20191010170332/Untitled-Diagram-183.png)
* Linear data structures: Elements are accessed in a sequential order but it is not compulsory to store all elements sequentially. Examples: Linked Lists, Stacks and Queues.
* Non – linear data structures: Elements of this data structure are accessed in a non-linear order. Examples: Trees and graphs.
-----
## Array([Practice](https://github.com/alkamaazmi/Data-Structures-and-Algorithms/tree/main/Array))

An array is a collection of items of same data type stored at contiguous memory locations.

The array elements can be accessed in constant time by using the index of the particular element as the
subscript.

Remember: “Location of next index depends on the data type we use”. 

![](https://media.geeksforgeeks.org/wp-content/uploads/array-2.png)

#### Why Constant Time for Accessing Array Elements?

To access an array element, First the size of an element of that data type is calculated and then it is multiplied with the index of the element to get the value to be added to the base address.

This process takes one multiplication and one addition. Since these two operations take constant
time, we can say the array access can be performed in constant time.

----
## Linked List([Practice](https://github.com/alkamaazmi/Data-Structures-and-Algorithms/tree/main/Linked%20List))

A linked list is a linear data structure, in which the elements are not stored at contiguous memory locations. The elements in a linked list are linked using pointers.They include a series of connected nodes. Here, each node stores the data and the address of the next node.

It is basically chains of nodes, each node contains information such as data and a pointer to the next node in the chain. In the linked list there is a head pointer, which points to the first element of the linked list, and if the list is empty then it simply points to null or nothing.

![](https://media.geeksforgeeks.org/wp-content/uploads/20220816144425/LLdrawio.png)

#### Difference between Array and Linked List

![](https://media.geeksforgeeks.org/wp-content/uploads/20220525085238/Screenshot20220525085154.png)

#### What Are the Types of Linked Lists?
* Singly Linked Lists
* Doubly Linked List
* Circular Linked List
* Doubly Circular Linked List

### Singly Linked Lists([Implementation](https://github.com/alkamaazmi/Data-Structures-and-Algorithms/blob/main/Linked%20List/singlyLinkedList.cpp))

Singly Linked Lists consists of a number of nodes in which each node stores the data and the address of the next node. The link of the last node in the list is
NULL, which indicates the end of the list.

![](https://media.geeksforgeeks.org/wp-content/uploads/singly-linkedlist.png)

### Doubly Linked List

In a doubly linked list, a node consists of three parts: node data, pointer to the next node in sequence (next pointer) , pointer to the previous node (previous pointer).

![](https://media.geeksforgeeks.org/wp-content/uploads/20220712180755/Doublylinkedlist.png)

### Circular Linked List

 A circular linked list is a unidirectional linked list where each node points to its next node and the last node points back to the first node, which makes it circular.

![](https://media.geeksforgeeks.org/wp-content/uploads/20220712181336/Circularlinkedlist.png)

### Doubly Circular Linked List

A doubly circular linked list is a linked list where each node points to its next node and its previous node and the last node points back to the first node and first node’s previous points to the last node.

![](https://media.geeksforgeeks.org/wp-content/uploads/20220830114920/doubly-660x177.jpg)

---
## Stack([Practice](https://github.com/alkamaazmi/Data-Structures-and-Algorithms/tree/main/Stack))

Stack is a linear data structure in which insertion and deletion are done at one end, called
top. The last element inserted is the first one to be deleted. It follows the principle of Last In First Out (LIFO) or First in Last out (FILO) list.

When an element is inserted in a stack, the concept is called push, and when an element is removed from the stack, the
concept is called pop.Trying to pop out an empty stack is called underflow and trying to push an
element in a full stack is called overflow.

![](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20221219100314/stack.drawio2.png)

#### Implementation

* [Simple array based implementation](https://github.com/alkamaazmi/Data-Structures-and-Algorithms/blob/main/Stack/stack-using-array.cpp)
* [Linked lists implementation](https://github.com/alkamaazmi/Data-Structures-and-Algorithms/blob/main/Stack/stack-using-linkedlist.cpp)
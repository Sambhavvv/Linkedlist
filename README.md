# Linkedlist

A linked list is a linear data structure that includes a series of connected nodes. Here, each node stores the data and the address of the next node. 
For example, You have to start somewhere, so we give the address of the first node a special name called HEAD. Also, the last node in the linked list can be identified because its next portion points to NULL.
Linked lists can be of multiple types: singly, doubly, and circular linked list.

# Representation of Linked List:-
Each node consists:a data item, an address of another node

The power of a linked list comes from the ability to break the chain and rejoin it. E.g. if you wanted to put an element 4 between 1 and 2, the steps would be:
![234295252-007e3b02-1878-45bb-8a74-0ca0fc23c172](https://user-images.githubusercontent.com/96248783/234404455-3a75b91c-12fc-4062-b745-b14c73897f64.png)


Create a new struct node and allocate memory to it.
Add its data value as 4.  
Point its next pointer to the struct node containing 2 as the data value.
Change the next pointer of "1" to the node we just created.
# Linked List Utility

*Lists are one of the most popular and efficient data structures, with implementation in every programming language like C, C++, Python, Java, and C#.
*Apart from that, linked lists are a great way to learn how pointers work. By practicing how to manipulate linked lists, you can prepare yourself to learn more advanced data structures like graphs and trees.


# Complexity:-
Time Complexity


<img width="455" alt="234297003-b54653b1-e6af-4ad1-9664-41db6b709d2d" src="https://user-images.githubusercontent.com/96248783/234405046-5f15d459-d81e-4f4a-b229-26c1236472ea.png">


# Space Complexity:- O(n)

Linked List Applications:-

1.Dynamic memory allocation
2.Implemented in stack and queue
3.In undo functionality of softwares
4.Hash tables, Graphs





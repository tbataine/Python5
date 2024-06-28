###Data Structures
One of the essential elements in working with Python is to have at one's command a working knowledge and understanding of a number of inbuilt and commonly used data structures, which become basic to the storing and manipulation of data efficiently. Some of the important data structures in Python are:

### Linked List
A **Linked List** is a linear data structure wherein the elements are stored in nodes. Each node consists of an element of data and a reference—a 'link'—to the next node in the sequence. No actual reallocation of memory for the whole structure is needed for any position of insertion or removal of elements, and hence it is very efficient in insertion or removal of elements at any position.

### Doubly Linked List
A **Doubly Linked List** can be thought of as being similar to a linked list, but the difference is that with each node, there comes an additional reference to the previous node besides just the next node. It allows traversal in both forward and backward directions, thus making operations like insertion and deletion more efficient than a singly linked list.

### Stack
**Stack**: A Last-In-First-Out (LIFO) data structure where elements are added and removed from the same end, called the top. This supports two major operations: `push` adding an element to the top, and `pop` removing and returning the top element.

### Queue
A **Queue** is actually a First-In First-Out structure of data in which one adds elements at the rear—enqueue—and removes them from the front, also called dequeue. It supports operations such as `enqueue`, which adds an element to the rear; and `dequeue`, which removes and returns the front element.

### Binary Search Tree BST
A **Binary Search Tree (BST)** is a binary tree data structure having no more than two children, known as the left child and right child for each node. The value of the key in nodes of the left subtree is less and the value of the key in nodes of the right subtree is greater, compared to the root node. This property allows performing an effective search, insertion, and deletion in the tree.

### Tree Traversal
Tree Traversal is a process of accessing or visiting each node in a tree data structure and performing some work on every visited node. Common traversal strategies include the following: Inorder Traversal: First, the left subtree should be visited, then the root, and lastly the right. Preorder Traversal: One should start from the root node, then the left subtree, and end with the right. Postorder Traversal: Left subtree, right subtree, and then root.
These traversal strategies are of paramount importance for analyzing and manipulation of trees in sorting, searching, and expression evaluation algorithms.

### Useful links:
- https://docs.python.org/3/tutorial/datastructures.html
- https://www.geeksforgeeks.org/python-data-structures/

### Conclusion
These data structures are of a fundamental nature in computer science and find very wide applications ranging from algorithm designing to software development. In all these data manipulation requirements, it is very essential to know their properties and operations.
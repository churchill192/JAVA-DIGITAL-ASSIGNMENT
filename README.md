# JAVA DIGITAL ASSIGNMENT
##                                  Merkle Tree
### Introduction
Merkle tree also known as hash tree is a data structure used for data verification and synchronization. 
It is a tree data structure where each non-leaf node is a hash of it’s child nodes. All the leaf nodes are at the same depth and are as far left as possible. 
It maintains data integrity and uses hash functions for this purpose. 


Hash Functions
       A hash or hash-value or a message digest is an array of fixed size random characters  generated when a message  or data is passed through an a  Mathematical algorithm. 
These mathematical algorithms are one way functions meaning, we can generate the output from input but not vice-versa. It has to be deterministic, meaning the input should always maps to same output regardless of the number of times it passed through it.  
Y(I) = O, where
Y  = Our hash function
I    = Input 
O  =  Output. 
Even a small change in the input produces completely output. This property is also known as avalanche effect.
Y(I') = O' 
These mathematical algorithms with the above properties are also known as Hash Functions.



### Architecture
![Architecture of Merkle Tree](C:\Users\churchill\Documents\GitHub\JAVA-DIGITAL-ASSIGNMENT\image.jpg) 

![Architecture of Merkle Tree]("C:\Users\churchill\Documents\GitHub\JAVA-DIGITAL-ASSIGNMENT\Hash_Tree.png") 

### Merkle Tree Implementation in Java
Merkle Tree Implementation in Java:
In this example implementation, We are going to implement binary merkle tree. As the first step, let's define the node. Like a regular tree, it has a  data field to store the hash and left and right pointers to point to left  child and right child of the binary tree.

### Reference:
https://www.pranaybathini.com/2021/05/merkle-tree.html






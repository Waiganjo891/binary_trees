A C tutorial about Binary trees

In computer science, a binary tree is a tree data structure in which each node has at most two children, referred to as the left child and the right child. That is, it is a k-ary tree with k = 2. A recursive definition using set theory is that a binary tree is a tuple (L, S, R), where L and R are binary trees or the empty set and S is a singleton set containing the root.

Filename: 0-binary_tree_node.c

Task
Write a function that creates a binary tree node. Where parent is a pointer to the parent node of the node to create and value is the value to put in the new node. When created, a node does not have any child. Your function must return a pointer to the new node, or NULL on failure.

Filename: 1-binary_tree_insert_left.c

Task
Write a function that inserts a node as the left-child of another node where parent is a pointer to the node to insert the left-child in and value is the value to store in the new node. Your function must return a pointer to the created node, or NULL on failure or if parent is NULL. If parent already has a left-child, the new node must take its place, and the old left-child must be set as the left-child of the new node.

Filename: 2-binary_tree_insert_right.c

Task
Write a function that inserts a node as the right-child of another node where parent is a pointer to the node to insert the right-child in and value is the value to store in the new node. Your function must return a pointer to the created node, or NULL on failure or if parent is NULL, if parent already has a right-child, the new node must take its place, and the old right-child must be set as the right-child of the new node.



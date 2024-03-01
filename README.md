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
Write a function that inserts a node as the right-child of another node where parent is a pointer to the node to insert the right-child in and value is the value to store in the new node. Your function must return a pointer to the created node, or NULL on failure or if parent is NULL, if parent already has a right-child, the new node must take its place, and the old right-child must be set as the right-child of the new

Filename: 3-binary_tree_delete.c

Task
Write a function that deletes an entire binary tree where tree is a pointer to the root node of the tree to delete.

Filename: 4-binary_tree_is_leaf.c

Task
Write a function that checks if a node is a leaf where node is a pointer to the node to check your function must return 1 if node is a leaf, otherwise 0.

Filename: 5-binary_tree_is_root.c

Task
Write a function that checks if a given node is a root where node is a pointer to the node to check your function must return 1 if node is a root, otherwise 0.

Filename: 6-binary_tree_preorder.c

Task
Write a function that goes through a binary tree using pre-order traversal where tree is a pointer to the root node of the tree to traverse and func is a pointer to a function to call for each node. The value in the node must be passed as a parameter to this function.

Filename: 7-binary_tree_inorder.c

Task
Write a function that goes through a binary tree using in-order traversal where tree is a pointer to the root node of the tree to traverse and func is a pointer to a function to call for each node. The value in the node must be passed as a parameter to this function.

Filename: 8-binary_tree_postorder.c

Task
Write a function that goes through a binary tree using post-order traversal where tree is a pointer to the root node of the tree to traverse and func is a pointer to a function to call for each node. The value in the node must be passed as a parameter to this function. If tree or func is NULL, do nothing

Filename: 9-binary_tree_height.c

Task
Write a function that measures the height of a binary tree where tree is a pointer to the root node of the tree to measure the height. If tree is NULL, your function must return 0

Filename: 10-binary_tree_depth.c

Task
Write a function that measures the depth of a node in a binary tree where tree is a pointer to the node to measure the depth. If tree is NULL, your function must return 0

Filename: 11-binary_tree_size.c

Task
Write a function that measures the size of a binary tree where tree is a pointer to the root node of the tree to measure the size. If tree is NULL, the function must return 0

Filename: 12-binary_tree_leaves.c

Task
Write a function that counts the leaves in a binary tree where tree is a pointer to the root node of the tree to count the number of leaves. If tree is NULL, the function must return 0. A NULL pointer is not a leaf

Filename: 13-binary_tree_nodes.c

Task
Write a function that counts the nodes with at least 1 child in a binary tree where tree is a pointer to the root node of the tree to count the number of nodes. If tree is NULL, the function must return 0. A NULL pointer is not a node

Filename: 14-binary_tree_balance.c

Task
Write a function that measures the balance factor of a binary tree where tree is a pointer to the root node of the tree to measure the balance factor. If tree is NULL, return 0

Filename: 15-binary_tree_is_full.c

Task
Write a function that checks if a binary tree is full where tree is a pointer to the root node of the tree to check. If tree is NULL, your function must return 0

Filename: 16-binary_tree_is_perfect.c

Task
Write a function that checks if a binary tree is perfect where tree is a pointer to the root node of the tree to check. If tree is NULL, your function must return 0

Filename: 17-binary_tree_sibling.c

Task
Write a function that finds the sibling of a node where node is a pointer to the node to find the sibling. Your function must return a pointer to the sibling node, if node is NULL or the parent is NULL, return NULL, f node has no sibling, return NULL.

Filename: 18-binary_tree_uncle.c

Task
Write a function that finds the uncle of a node where node is a pointer to the node to find the uncle. Your function must return a pointer to the uncle node, if node is NULL, return NULL, if node has no uncle, return NULL.

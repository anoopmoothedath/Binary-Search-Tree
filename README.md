# Binary-Search-Tree

# Algorithm

## Insert Node in BST
````
insertNodeInBST(BSTNODE root, int ele)
Step-1: Create a new node temp with given value ele and set its left and rightfield to NULL.
Step-2: If root is equal to NULL set temp as root.
Step-3: If root is not equal to empty , check if the ele is smaller or larger than the root node
Step-4: If ele is smaller than or equal to the node, then move to its left child. If ele is larger than the node, then move to its right child.
Step-5: Repeat the steps 3 and 4 until we reach a leaf node.
Step-6: After reaching a leaf node, then insert the newNode as left child if newNode is smaller or equal to that leaf else insert it as right child.
````
## Inorder Traversal
````
inorderInBST(BSTNODE root)
Step-1: Traverse the elements in the left subtree of the root node. i.e call inorderInBST(root->left).
Step-2: Visit the root node i.e. print the data field of the root
Step-3: Traverse the elements in the right subtree of the root node. i.e call inorderInBST(root->right).
````
## Preorder Traversal
````
preorderInBST(BSTNODE root) is as follows
Step-1: Visit the root node
Step-2: Traverse the elements in the left sub tree of the root node. i.e call preorderInBST(root->left).
Step-3: Traverse the elements in the right sub tree of the root node. i.e call preorderInBST(root->right).
````
## Postorder Traversal
 ````
postorderInBST(BSTNODE root)
Step-1: Traverse the elements in the left sub tree of the root node. i.e call postorderInBST(root->left).
Step-2: Traverse the elements in the right sub tree of the root node. i.e call postorderInBST(root->right).
Step-3: Visit the root node
````
## Searching
````
searchNodeInBST(BSTNODE root, int ele)
Step-1: IF ROOT -> DATA = ITEM OR ROOT = NULL, Return ROOT
Step-2: ELSE IF ROOT < ROOT -> DATA
Step-3: Return search(ROOT -> LEFT, ITEM)
Step-4: ELSE, Return search(ROOT -> RIGHT,ITEM)
````

# Activities

## Task 1: Tree Definition

- Answer at least 5 questions from the following link. Make sure you write the question as well as the answer.
  https://opendsa-server.cs.vt.edu/OpenDSA/Exercises/Binary/DefSumm.html

      Select the one true statement.

       () Every binary tree is either complete or full
       () Every complete binary tree is also a full binary tree
       () Every full binary tree is also a complete binary tree
       () No binary tree is both complete and full
       (X) None of the above 

      Suppose T is a binary tree with 14 nodes. What is the minimum possible height of T?

        3

      What is the minimum number of nodes in a complete binary tree with height 3?

        8

      What is the minimum number of nodes in a full binary tree with height 3?

       7 

      Which statement is false?

        ()  Every node in a binary tree has exactly two children
        (X)  Every binary tree has at least one node
        ()  Every non-empty binary tree has exactly one root node
        ()  Every non-root node in a binary tree has exactly one parent
        ()  None of the above










## Task 2

- Explain how the code in ./src/bt.cpp works. Refer to the following link:
  https://www.geeksforgeeks.org/binary-tree-array-implementation/

  Like it says on top: C++ implementation of tree using array, numbering starting from 0 to n-1.

      The functions used are:

          root(char key): sets the root node of the tree to the given key if it doesn't already exist.
          set_left(char key, int parent): sets the left child of a parent node with the given key. It checks if the parent node exists before setting the child node.
          set_right(char key, int parent): sets the right child of a parent node with the given key. It checks if the parent node exists before setting the child node.
          print_tree(): prints the entire tree in a graphical format with '-' representing an empty node.

      In the main() function, the tree is created by setting the root node to 'A', and then adding child nodes 'B' and 'C' to the root, followed by their respective child nodes 'D' and 'E' and 'F'. Finally, the print_tree() function is called to print the entire tree in a graphical format.

## Task 3: Tree Traversal

Refer to te following links. Discuss the difference between the different ways binary trees can be traversed.

- [Pre-order Traversal](https://opendsa-server.cs.vt.edu/OpenDSA/AV/Binary/btTravPreorderPRO.html)
- [Post-order Traversal](https://opendsa-server.cs.vt.edu/OpenDSA/AV/Binary/btTravPostorderPRO.html)
- [In-order Traversal](https://opendsa-server.cs.vt.edu/OpenDSA/AV/Binary/btTravInorderPRO.html)


          Pre-order traversal: Visit the root node, then recursively visit the left subtree, then recursively visit the right subtree.
          
          Post-order traversal: Recursively visit the left subtree, then recursively visit the right subtree, then visit the root node.

          In-order traversal: Recursively visit the left subtree, then visit the root node, then recursively visit the right subtree.


## Task 4: Individual (at home)

- Answer at least 5 questions from the following link. Make sure you write the question as well as the answer.
  https://opendsa-server.cs.vt.edu/OpenDSA/Exercises/Binary/TravSumm.html

      1.If you are given the order of the nodes as visited by a postorder traversal and the order of the nodes as visited by an inorder traversal, do you have enough information to reconstruct the original tree? Assume that the nodes all have unique values.

      True


      2.Why does function preorder2() presented in the Traversal module make only half as many recursive calls as function preorder()?

      Because only internal nodes get called


      3.The nn nodes in a binary tree can be visited in:
      Θ(n)Θ(n) time.

      In order to visit all nn nodes in a binary tree, we must traverse each node exactly once. Therefore, the time complexity for visiting all nodes in a binary tree is linear in terms of the number of nodes, i.e., Θ(n)Θ(n) time.


      4.When you print out the nodes of binary tree, the leaf nodes appear in the same relative order for the preorder, inorder, and postorder traversals.

      False.


      5.Visiting each element in a tree is known as:

      Traversing


- Answer at least 5 questions from the following link. Make sure you write the question as well as the answer.
  https://opendsa-server.cs.vt.edu/OpenDSA/Exercises/Binary/Treeprobs.html

      1.How many descendents does the root of this tree have?
        There was 8. Need to count all other than the top one.


      2.What is the depth of this tree?
        Trees have height -- they do not have depth

      3.How many nodes in the tree have at least one sibling?
        6 (Siblings must have the same parent. If a node has two children, then each such child has a sibling.)


      4.Which statement is correct?
        The tree was neither full nor complete

      5.How many leaf nodes does this tree have?
        there was 4 (Last individuals counted)
## Links

- https://cpp.sh/
- https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/BinaryTree.html
- https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/BinaryTreeTraversal.html

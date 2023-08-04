# Red-Black_Tree_Visualizer
The Red-Black Tree Visualizer is a web-based project that allows you to visualize the Red-Black Tree data structure. It supports common operations such as insert, delete, and find, and visualizes the tree structure using the Sigma.js library, and displays the tree structure along with the conditions and steps involved in each operation.. The project is built using HTML, CSS, and JavaScript, with no backend requirements.

Red-Black tree is a binary search tree in which every node is colored with either red or black. It is a type of self balancing binary search tree. It has a good efficient worst case running time complexity.

## Properties that every Red-Black Tree follows: 
  * Every node has a color either red or black.
  * The root of the tree is always black.
  * There are no two adjacent red nodes (A red node cannot have a red parent or red child).
  * Every path from a node (including root) to any of its descendants NULL nodes has the same number of black nodes.
  * Every leaf (e.i. NULL node) must be colored BLACK.

## Why Red-Black??
Most of the BST operations (e.g., search, max, min, insert, delete.. etc) take O(h) time where h is the height of the BST. The cost of these operations may become O(n) for a skewed Binary tree. If we make sure that the height of the tree remains O(log n) after every insertion and deletion, then we can guarantee an upper bound of O(log n) for all these operations. The height of a Red-Black tree is always O(log n) where n is the number of nodes in the tree. 

## Installation
 1)  Clone the repository:
 ` git clone https://github.com/akshaypatel67/Scapegoat-Tree-Visualizer.git`
 2) Navigate to the project directory.
 3) Open the index.html file in your preferred web browser.

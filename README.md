# Red-Black_Tree_Visualizer
The Red-Black Tree Visualizer is a web-based project that allows you to visualize the Red-Black Tree data structure. It supports common operations such as insert, delete, and find, and visualizes the tree structure using the Sigma.js library, and displays the tree structure along with the conditions and steps involved in each operation.. The project is built using HTML, CSS, and JavaScript, with no backend requirements.

Red-Black tree is a binary search tree in which every node is colored with either red or black. It is a type of self balancing binary search tree. It has a good efficient worst case running time complexity.


## Why Red-Black??
Most of the BST operations (e.g., search, max, min, insert, delete.. etc) take O(h) time where h is the height of the BST. The cost of these operations may become O(n) for a skewed Binary tree. If we make sure that the height of the tree remains O(log n) after every insertion and deletion, then we can guarantee an upper bound of O(log n) for all these operations. The height of a Red-Black tree is always O(log n) where n is the number of nodes in the tree. 

## Properties that every Red-Black Tree follows: 
  * Every node has a color either red or black.
  * The root of the tree is always black.
  * There are no two adjacent red nodes (A red node cannot have a red parent or red child).
  * Every path from a node (including root) to any of its descendants NULL nodes has the same number of black nodes.
  * Every leaf (e.i. NULL node) must be colored BLACK.

## Technologies Used
  * HTML: The markup language used for creating the structure of the web page.
  * CSS: A utility-first CSS framework for styling the web page.
  * JavaScript: The programming language used for implementing the tree operations and interacting with the DOM.
  * Sigma.js: A JavaScript library for interactive graph visualizations.

## Installation
 1)  Clone the repository:
 ` git clone https://github.com/jaysathiya64/Red-Black_Tree_Visualizer.git`
 2) Navigate to the project directory.
 3) Open the index.html file in your preferred web browser.

## Usage
    
To use the Red_Black Tree Visualizer, follow these steps:

 1) Download the project source code or clone the repository to your local machine.

 2) Open the home.html file in a modern web browser that supports JavaScript.

 3) On the web page, you will see a tree visualization area and control options.

 4) To perform operations on the tree, use the following controls:
   * Insert: Enter a key value in the "Insert Key" input field and click the "Insert" button.
   * Delete: Enter a key value in the "Delete Key" input field and click the "Delete" button.
   * Find: Enter a key value in the "Find Key" input field and click the "Find" button.
5) The visualization will update accordingly, displaying the tree structure and highlighting the nodes involved in each operation.

## Snapshots
### Insert the nodes
![image](https://github.com/jaysathiya64/Red-Black_Tree_Visualizer/assets/126950992/ba0ad1bf-cead-480e-a4ee-78b1fa40ac74)<hr>

### Delete the node: 36
  ![image](https://github.com/jaysathiya64/Red-Black_Tree_Visualizer/assets/126950992/259808b7-b491-4e28-88af-8c16f4ea23d0)<hr>

### Find the node:
  ![image](https://github.com/jaysathiya64/Red-Black_Tree_Visualizer/assets/126950992/e823bbe1-af24-4dbc-a3fd-b7af7581225d)





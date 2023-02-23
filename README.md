# DOM Traversing

You can navigate the node tree using node relationships.

    - The entire document is a document node
    - Every HTML element is an element node
    - The text inside HTML elements are text nodes
    - Every HTML attribute is an attribute node (deprecated)
    - All comments are comment nodes

![alt text](./assets/pic_htmltree.gif "HTML Tree")

## Node Relationships
The nodes in the node tree have a hierarchical relationship to each other.

The terms parent, child, and sibling are used to describe the relationships.

    - In a node tree, the top node is called the root (or root node)
    - Every node has exactly one parent, except the root (which has no parent)
    - A node can have a number of children
    - Siblings (brothers or sisters) are nodes with the same parent

<html>

  <head>
    <title>DOM Tutorial</title>
  </head>

  <body>
    <h1>DOM Lesson one</h1>
    <p>Hello world!</p>
  </body>

</html>

![alt text](./assets/pic_navigate.gif "HTML Tree")
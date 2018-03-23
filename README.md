## Project Name:  Photo Gallery Application

### Course Title:
Web Application Development

### Assignment Date:  
March 23, 2018

### Student Name:  
Bonnie Gaupp

### Project Description:
This lesson uses JavaScript and basic properties of the BOM/DOM to build a photo gallery that can change the number of displayed images bases on a user's interaction with the page.

### View Project:
https://bgaupp.github.io/lesson6_javascript3/

### Lessons Learned in the Assignment:
1. JavaScript treats web page content as a set of related components ("objects") - every element on a page is an object. The Browser Object Model (BOM) orders those objects into a hierarchy. The "Window Object" represents the top object of a web browser window. All other BOM objects are contained within that window object. The Document Object is its own object within the BOM and represents the web page that's displayed in a browser. The Document Object Model (DOM) provides a structure for changing the contents of these web page elements. JavaScript represents each of those page elements with its own set of properties and methods.
2. The DOM is organized into a branching tree - each item in a DOM tree is called a node. The "element," "attribute," and "text" content nodes are the most commonly used nodes. Aspects of the DOM include: Identification - obtaining specific node references, Traversal - moving around the DOM tree, Node Manipulation - getting or setting aspects of a node, Tree Manipulation - changing the structure of the page. It is possible to add, remove, and clone nodes, though newly created nodes are independent of the DOM tree. To attach a new node, one must utilize the "appendChild" method to attach a node to an existing parent node. Cloning nodes uses Boolean values to determine how much of the node is cloned. If true, the method clones the child node. If false, the method clones only the parent node.
3. Dynamic HTML can change the presentation of web page content without a user needing to reload the page. By changing variables with JavaScript, a fully loaded page can function based on user's interactions. A developer can access and change elements using certain tags for various html, css, and js properties. To access and change elements within the Document object, one can call IDs, tags, classes, names, selectors, or attributes to change css and html properties on a page. Calling these elements requires certain commands and methods in JavaScript based on the type of element you are changing. 
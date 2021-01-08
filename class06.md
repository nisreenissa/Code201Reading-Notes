The value when you call a function called arguments , they can be variables or values 
Functions can return more than one value using an array. 
A function with no name is called an anonymous
function. 
There are three types of loop: for, while, and do ... while. Each repeats a set of statements. 
As a browser loads a web page, it creates a model of that page.
The model is called a DOM tree, and it is stored in the browsers' memory.

DOM trees have four types of nodes: document nodes,
element nodes, attribute nodes, and text nodes. 


Accessing and updating the DOM tree involves two steps:
1: Locate the node that represents the element you want to work with.
2: Use its text content, child elements, and attributes. 

The terms elements and element nodes are used interchangeably
but when people say the DOM is working with an element,
it is actually working with a node that represents that element. 

Dom queries : when you want to work with the elemnt more than once 

If a method can return more than one node, it will always return a Nodelist, which is a collection of nodes (even if it only finds one matching element)

A Nodelist is a collection of element nodes. Eachnode is given an index number (a number that starts at zero, just like an array

There are two ways to select an element from a Nodelist:
The item() method and array syntax. 

when you have a nodelist , you can loop through  each node in the collection and apply the same statement to each.

When you have an element node, you can selectanother element in relation to it using these five properties. This is known as traversing the DOM. 
Traversing the DOM can be difficult becausesome browsers add a text node whenever they come across whitespace between elements. 

Theree are two diffrent approaches to adding and remocing cotent from dom tree :the innerHtml prperty and dom manipulation 

You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax. 

An element node can contain multiple text nodes and child elements that are siblings of each other. 
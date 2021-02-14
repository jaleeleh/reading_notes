# CH3:OBJECT LITERAL,javascript
Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names.
 * IN AN OBJECT: VARIABLES BECOME
KNOWN AS **PROPERTIES**
* IN AN OBJECT: FUNCTIONS BECOME
KNOWN AS **METHODS**
* the name of property and method called **key**
* The value of a property can be a st ring, number, Boolean, array, or
even another object. The va lue of a method is always a function.
* literal notation:the  easiest way to creat an object.

# CH 5:Document Object Model
The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules.
It is implemented by all major browser makers, and covers two primary areas:
1. MAKING A MODEL OF THE HTML PAGE
2. ACCESSING AND CHANGING THE HTML PAGE
As a browser loads a web page, it creates a model of that page.
The model is called a DOM tree, and it is stored in the browsers' memory.
It consists of four main types of nodes.
* As a browser loads a web page, it creates a model of that page.
The model is called a DOM tree, and it is stored in the browsers' memory.
It consists of four main types of nodes.
* Accessing and updating the DOM tree involves two steps:
1. ACCESS THE ELEMENTS.
2. WORK WITH THOSE ELEMENTS
*catching dom queries:methods that find elemens inside the dom .
* getElementByld():
Selects an individual element given the value of its i d attribute .
The HTML must have an id attribute in order for it to be selectable
* getEl ements ByClassName( ):
Selects one or more elements given the va lue of their cl ass attribute.
The HTML must have a cl ass attribu te for it to be selectable.
This method is faster than querySe 1ectorA11 () .
* From an element node, you can access and update its content using properties such as textContent and
i nnerHTML or using DOM manipulation techniques.
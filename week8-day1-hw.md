__Questions (Look up answers online answer each in markdown and submit)___

___What is Z-index?___

>Z-index is a css property that dictates the position of overlap (z-order) between positioned elements. A larger z-index will cover those with a smaller z-index.

___How do you make a Circle in CSS?___
<br>There are several ways to make a circle in css. 

>clip-path: circle(40%); 
<br>creates a mask

> height: 50px;
  width: 50px;
  background-color: red;
  border-radius: 50%; 
  <br>creates a shape

> OR, SVG (scalable vector graphics) <svg width="100" height="100">
  <circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" />
</svg>


___What is a Vendor Prefix and What is it's Purpose?___

>A vendor prefix is a way for browsers to use experimental/non-stable css properties and Javascript APIs until they were made fully compatible with that browser. 

___What is the difference between CSS Grid and Flexbox?___
>Flex-box's layout design is best suited for one-dimensional layouts making use of either a row or column and its properties. Grid was designed to be used for creating two-dimensional layouts: manipulating rows and columns with more flexibility.

How might you Speed Up a Slow App? hint Google Lighthouse in Chrome Developer Tools....
>Text-based resources should be served with compression (gzip, deflate or brotli) to minimize total network bytes.<br>
Reduce unused JavaScript and defer loading scripts until they are required to decrease bytes consumed by network activity<br>
Set an explicit width and height on image elements to reduce layout shifts<br>
Resources are blocking the first paint of your page. Consider delivering critical JS/CSS inline and deferring all non-critical JS/styles<br>
HTTP/2 offers many benefits over HTTP/1.1, including binary headers and multiplexing<br>
Text-based resources should be served with compression (gzip, deflate or brotli) to minimize total network bytes.


What is CRUD?

>CRUD refers to the four functions that are considered necessary to implement a persistent storage application: create, read, update and delete. Persistant storage is just that, persistant, and will be acceesible even after your machine is powered down.

What is OOP?

>Object-Oriented Programming (OOP) is a programming paradigm that relies on the concept of classes and objects. It approaches the creation of a program through the development of eusable pieces of code (classes), that are used to create individual instances of objects.
# Mentor Interface - Solution for Project tracing intro component

## Table of Contents

- #overview
  - #challenge
- #links
- #my-process
  - #built-in with
  - #what-have-I-learned
  - #continued development
  - #useful resources
- #author
- #confirmations


## Overview

### Challenge

Users have the ability to:
- View the optimal layout of components depending on the screen size of their device
- View hover states for all interactive elements on the page


### Links

- Solution URL: 
- URL of the live site: 

## My process

CSS is stored in a separate file. To link to this file from an HTML page, the <link> tag is used between the <head> tags, as shown, which assumes that the style sheet is stored in a file named "style.css". Embedded CSS are styles that are in the header of an HTML document that requires styling. For example, we would like the text in this HTML document to be bold.If there is a lot of JavaScript code– it is put in a separate file, which, as a rule, has an extension.js. But even if our code is small, we wanted it to be on another file. To include JavaScript code from an external file in an HTML document, use the src (source) attribute of the <script> tag. Its value should be the URL of the file containing the JS code.

### Built with

- HTML5 semantic markup
- Custom CSS properties as well as internal style
- JavaScript programming language that allows you to create dynamically updated content

### What I learned

In this practical work, we have studied some JavaScript properties that are also used in the process of this work. A JavaScript function is a block of code designed to perform a specific task.
A JavaScript function is executed when it is called (called) "something".
 There are 3 ways to declare a JavaScript variable:
Using var
Using let
Using const
In this practical work, const is used.
Switch between adding and removing a class name from an element using JavaScript.Switch between adding the class name to the div element with id = "" (in this example, we use the button to switch the class name). The classList property returns the name(s) of the element class as a DOMTokenList object.
This property is useful for adding, removing, and switching CSS classes for an element.
The classList property is read-only, but it can be changed using the add() and remove() methods.
Cross-browser solution: The classList property is not supported in IE9 and earlier versions. However, you can use the className property or regular expressions for a cross-browser solution.
Switching between the class name for the element.
The first parameter removes the specified class from the element and returns false.
If the class does not exist, it is added to the element, and the return value is true.
The optional second parameter is a boolean value that forcibly adds or removes a class, regardless of whether it already exists or not. For example:
Delete class: element.classList.toggle ("classtoremove", false);
Add a class: element.classList.toggle ("classtoadd", true);
The @import rule is used to import one style sheet into another style sheet. This rule also supports media queries so that the user can import a media-dependent stylesheet. The @import rule should be declared at the top of the document after any @charset declaration.
Using an import rule in itself is not a bad practice. You just have to keep in mind that imports are processed only after the file containing them has been uploaded.

``html
Some HTML code that I'm proud of.
 				<button class="hamburger" id="hamburger">
					<img
						class="icon-hamburger"
						src="./images/icon-hamburger.svg"
						alt="hamburger-icon"
					/>
					<img
						class="icon-close"
						src="./images/icon-close.svg"
						alt="close-icon"
					/>
				</button>

```
``css
 proud-of-this-css
 <style>
body::after {
	background-color: var(--light-grayish-blue);
	border-bottom-left-radius: 100px;
	content: '';
	position: absolute;
	top: 0;
	right: 0;
	height: 50vh;
	width: 50vw;
	z-index: -1;
}
 </style>
```
`js
<script>
hamburger.addEventListener('click', e => {
	body.classList.toggle('show-nav');});
</script>
``


### Continued development

I want to keep focusing on developing ideas for future projects. I want to improve and manage
the priority of tasks.But, in our opinion, the main thing is to approach the project consciously and try
use professional tools and approaches that you have learned about.That is why the constant development and pumping of yourself allows you to be ready for any situations to solve problems. 
But, of course, we understand that the focus of attention can vary depending on our desire and direction. We also want to continue to make a lot of creative websites.

### Useful resources

- https://www.w3schools.com/js/default.asp - For some reason, it helped me a lot. I really liked
the templates found there, and I will use them in the future.
- https://developer.mozilla.org/ru/docs/Learn/JavaScript - This is an amazing site that helped me finally
understand. I would recommend this to anyone who is still learning this JavaScript concept. 


## Author

- Website - [Alikhan Serikov and Ayakoz Mukiyat] (https://nauryzrakhmanov .github.io/aaa /)
- Mentor on the interface - [Togzhan Kurmanbek] 
- Instagram - [@ayagoozm] (https://www.instagram.com/ayagoozm /) 
              [@sal1khb](https://www.instagram.com/sal1khb/)


## Thank you
Thanks to our mentor on the project Togzhan Kurmanbek.
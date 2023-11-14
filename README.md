# Mastering CSS: Advanced Tools and Techniques
--


## CSS Positioning
- There are four main types of positioning that you will see most often - static, relative, absolute, and fixed.
	- **Todo**: In groups research the type you are assigned and how it works, be ready to present what you learn to the entire class in two minutes or less. 
- Static positioning is what all elements have by default. 
- Relative and absolute work together - elements can be positioned absolutely relative to their container.
- Fixed position elements are essentially absolute relative to the window no matter where they are in the DOM. A.K.A. the window is always the relative parent.
- **Todo**: Try to replicate the following mockup using any of the following: margins, padding, floats, positioning. 

![](https://raw.githubusercontent.com/arun-instructor/FEWD-Arun/master/week_02_layout/04_layout/img/stackers.png)

## CSS Transitions
- Allow us to add an effect without using JavaScript or Flash.  
- Allow you to go between different element states smoothly. 
- You must specify: the CSS property you want to add an effect to and the duration of the effect. 
- Transitions are controlled using the shorthand transition property. 
- This is the syntax:

 `transition: property duration easing;`

- **Todo**: Research a transition of your choice and put it in to practice. Choose something simple :) 

## Pseudo Classes in CSS
- A pseudo class is a keyword added to selectors that specifies a special state of the element to be selected. 
- For example :hover will apply a style when the user hovers over the element specified by the selector. 
- This is the syntax:

 ```
 selector:pseudo-class {
 	   property: value;
 } 
 ```
- The`:nth-child selector` allows you to select one or more elements based on their source order.

## CSS Selectors
- Selectors allow you to select DOM elements for styling. 
- Take a look at some of the most common CSS3 selectors 
[here.](http://www.w3schools.com/cssref/css_selectors.asp)
- **Todo**: Practice using a selector of your choice on codepen. 

## Fun Features with CSS
- The **border-radius** property allows you to round the borders to elements. 
	- Ex: 
	
		```
		div {
		    border: 2px solid #a1a1a1;
		    padding: 10px 40px; 
		    background: #dddddd;
		    width: 300px;
		    border-radius: 25px;
		}
		
		```
- **Gradients(linear and radial)** let you display smooth transitions between two or more colors.
- The **transform** property allows you to scale, move or skew an element. 
	- Ex:

		``` 
		div {
			-ms-transform: rotate(10deg); 
			-webkit-transform: rotate(10deg); 
			transform: rotate(10deg);
	       	background-color: red;
	       	width: 100px;
       		height: 100px;
}
		
		```

## CSS Animations
- Can replace animations created by JavaScript or Flash. 
- The **@keyframes** rule is where the animation is actually created.
- Bind the animation to a specific selector by stating at least these two properties:

 	- Name of the animation
 	- Duration of the animation

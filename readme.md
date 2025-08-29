1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
Ans: The getElementById() function gets one element based on the given ID. 
The getElementsByClassName() function gets all of the elements with the same class. 
The querySelector() function gets the first found element based on the CSS selector. 
The querySelectorAll() function gets all of the found elements and formats them as a NodeList, and will remain static in that format. 

2. How do you create and insert a new element into the DOM?
Ans: I can create an element using document.createElement(). 
I can set the text content of the element using textContent and set most attributes using the setAttribute() function. 
I can add an element to the page using appendChild(), prepend(), before(), and after(). 

3. What is Event Bubbling and how does it work?
Ans: Event bubbling is the process of where an event begins at the child and works its way to the parent. 
If I click a button in a div, the button will fire that buttons event first then the div's event. 

4. What is Event Delegation in JavaScript? Why is it useful?
Ans: Event delegation is adding one listener to the parent instead of adding one to every child element. 
The parent knows what child is clicked by the event.target. 
This allows me to avoid writing sibling events for every sibling element when only the parent has to handle it.

5. What is the difference between preventDefault() and stopPropagation() methods?

Ans: The preventDefault() method will stop the browser from doing the default action. 
The stopPropagation() method will stop the event from bubbling up to parents which limits that event to only the element you just clicked on.
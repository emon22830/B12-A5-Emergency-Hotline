

###  Answer the following questions clearly:

1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?
   Ans: (a). getElementById(id) → Returns a single element with the specified id.
        (b). getElementsByClassName(class) → Returns a live HTMLCollection of all elements with the given class name.
        (c). querySelector(selector) → Returns the first element that matches a CSS selector.
        (d). querySelectorAll(selector) → Returns a static NodeList of all elements that match a CSS selector.



2. How do you **create and insert a new element into the DOM**?
   Ans: To create and insert a new element into the DOM, I will usually follow three steps:
        (a). Create the element using document.createElement("tagName").
        (b). Add content or attributes to it, like setting textContent or id.
        (c). Insert it into the page using a method such as appendChild(), append(), or prepend().


3. What is **Event Bubbling** and how does it work?
   Ans: Event bubbling means that when an event happens on an element, it first runs the handler on that element, and then it bubbles up to its parent, then the parent’s parent, and so on, until it reaches the top of the DOM.
   for example if you click a button inside a <div>, the button’s event runs first, then the <div>’s event runs, and it keeps going up.


4. What is **Event Delegation** in JavaScript? Why is it useful?
   Ans:Event Delegation is when you put a single event listener on a parent element to handle events from its child elements, instead of adding listeners to each child.

   It’s useful because it saves memory, makes the code cleaner, and also works for child elements that are added later.


5. What is the difference between **preventDefault() and stopPropagation()** methods?
   Ans: (a). preventDefault() → stops the browser’s default action from happening.
        for example stopping a link from opening or a form from submitting.

        stopPropagation() → stops the event from bubbling up (or going down during capturing) through the DOM.
        for example stopping a click on a button from also triggering the parent’s click handler.

   

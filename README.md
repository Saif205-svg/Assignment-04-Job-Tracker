### 1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
To target a specific ID name in JavaScript, we use the getElementById() method. Similarly, to target elements defined with the same class name in JavaScript, we can use the getElementsByClassName() method. With the help of this method, multiple elements that share the same class can be selected.

The querySelector() method returns the first element that matches a specified CSS selector. On the other hand, the querySelectorAll() method returns all elements that match a specified CSS selector, including classes and IDs.

Example:
querySelectorAll('.className', '#IdName');

### 2. How do you create and insert a new element into the DOM?
In the DOM, if we want to create a new element, we use the createElement() method. To insert data or another element into that created element, we can use the innerHTML property. Depending on the type of content we want to add, we can also use the innerText property for the created element.

### 3. What is Event Bubbling? And how does it work?
Event Bubbling occurs when we click on a button and the event does not stop at that button. Instead, it gradually propagates upward to its parent elements and is logged in the browser console. It starts from the target element and continues up to the HTML document.

### 4. What is Event Delegation in JavaScript? Why is it useful?
Event Delegation is a technique through which the element we click on can be removed. There are three main reasons for using it:
(i) It works dynamically.
(ii) It improves performance. For example, instead of adding 100 separate addEventListener() methods for 100 elements, we can handle them using delegation.
(iii) It helps keep the code clean.

### 5. What is the difference between preventDefault() and stopPropagation() methods?
The preventDefault() method prevents the default behavior of a website. In other words, when this method is used, the browser cannot perform the action it normally would.

The stopPropagation() method is mainly used in event bubbling. When stopPropagation() is applied, the event cannot bubble up to the parent elements.

The main difference between preventDefault() and stopPropagation() is that preventDefault() stops the browser default action, and stopPropagation() method stops the event from bubbling up through the DOM.
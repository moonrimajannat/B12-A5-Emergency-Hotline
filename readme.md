### 6. Answer the following questions clearly:

1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?
Answer: The methods getElementById, getElementsByClassName, querySelector and querySelectorAll are all used to select elements within the Document Object Model (DOM) in JavaScript. Although their functions are almost the same, there are differences in scope, return type, and selector support.
2. How do you **create and insert a new element into the DOM**?
Answer: There are two main steps to creating and inserting a new element into the Document Object Model (DOM) using JavaScript: creating the element and then attaching it to an existing part of the DOM.Steps to Create & Insert an Element:

1.Create → document.createElement("tagName")
2.Add content / attributes → element.textContent, element.innerHTML, element.setAttribute()
3.Find parent element → Select where you want to insert.
4.Insert into DOM → Add using appendChild, prepend, insertBefore, or append.
3. What is **Event Bubbling** and how does it work?
Answer: Event Bubbling is when an event occurs in a child element in the DOM, that event is first triggered in the child element, then propagates (bubble up) from parent → grandparent → up the document.
That is, the event goes from bottom to top.
4. What is **Event Delegation** in JavaScript? Why is it useful?
Answer: Event Delegation means placing an event listener on a parent element, so that the events of the child elements inside it can also be caught.
It is useful for-
1.Simplified Code and Maintainability
2.Improved the performance and memory efficient
3.Handling dynamic content
4.Reduced the complexity for the large structures
5. What is the difference between **preventDefault() and stopPropagation()** methods?
Answer: These two methods are almost same, but the work is completely different.Such as-
preventDefault() = Stops the browser's built-in functionality.
stopPropagation() = Stops the event flow from propagating up or down.


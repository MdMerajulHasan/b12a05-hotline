1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
    Answer: getElementById select the element with given id in "" or '' where getElementByClassName select the part of elements under the given classname in "" or ''. On the other hand querySelector need # before id name in "" or '' to select the element and querySelectorAll selects all of the part having the class name.

2. How do you create and insert a new element into the DOM?
    Answer: using document.createElement() method I create an element and use parentName.appendChild(childName) to insert it.

3. What is Event Bubbling and how does it work?
    Answer: Event bubbling is a mechanism in the DOM where a element trigger and the event goes to parent and grandparents also to trigger that event. It goes up to root and all element trigger if they has that event listener.

4. What is Event Delegation in JavaScript? Why is it useful?
    Answer: It is a technique to add single event listener to a common parent element. It will not be attached to separate listeners to many child elements. 

5. What is the difference between preventDefault() and stopPropagation() methods?
    Answer: a. preventDefault() prevents browser's default actions but stopPropagation prevents event's propagation like bubbling and capturing.
    b. preventDefault() is used to override standard browser behavior but stopPropagation() used to prevent an event on a child element form affecting its parent elements.
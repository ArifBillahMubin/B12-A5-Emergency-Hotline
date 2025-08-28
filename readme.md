# 📘 Assignment-005 

---

## Q1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

**Answer:**  
getElementById is use to find element by its ID.  
getElementsByClassName is use to find element by class name, it give a collection like array.  
querySelector select first element by CSS selector. querySelectorAll select all element by CSS selector.  

---

## Q2. How do you create and insert a new element into the DOM?

**Answer:**  
First we use document.createElement to make new element.  
Then we can add text or attribute inside it.  
After that use appendChild() or append() to insert this element inside the parent.  

---

## Q3. What is Event Bubbling and how does it work?

**Answer:**  
Event bubbling mean when event happen in child element, it go up to parent element step by step.  
Like if button clicked, first button handle it, then its div, then body.  

---

## Q4. What is Event Delegation in JavaScript? Why is it useful?

**Answer:**  
Event delegation mean put one event listener in parent and handle all child events from there.  
It is useful because we no need to put many listeners for every child, only parent handle all. 

---

## Q5. What is the difference between preventDefault() and stopPropagation() methods?

**Answer:**  
preventDefault() stop the default action of element, like stop form submit.  
stopPropagation() stop the event to go up to parent and stop bubbling.  

---

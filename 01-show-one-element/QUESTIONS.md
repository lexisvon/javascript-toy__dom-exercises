# DOM Atomic 01: Show One Element

## Questions

---

> If you click the link to reveal more text and then refresh the page, does the text remain revealed, or is it hidden again? Why?

The text goes back to being hidden because it goes to the original source code that was written. 

---

> Remove `window.addEventListener("load", function(){` (and the closing `})`) from **global.js**. Does the link still reveal the text? What is the purpose of this code that you've removed?

The link becomes broken. The purpose of this is to addEventListener on load of the window and create a function. Without this the addEventListner wouldn't work. 

---

> Describe the the `addEventListener` method. (Remember that there is a specific, technical, methodical way to describe methods. Your reply should match that format.)

The addEventListner attaches to the event handler, which is when a user clicks the mouse, and when the page has loaded. 

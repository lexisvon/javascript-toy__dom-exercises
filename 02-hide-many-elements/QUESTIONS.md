# DOM Atomic 02: Hide Many Elements

## Questions

---

> How did you go about selecting the DOM elements to hide? Describe the "contract" for that function.

The getElementsByClassName selected all of the elements I wanted to be hidden. This returns what we want selected by that class name as a nodelist object. Kind of like an array. 

---

> Describe how you were able to hide each element. Were you able to do it as one operation, or did you use a loop of some kind? Describe the "contracts" that were utilized to accomplish your goal.

I tried accomplishing it as one operation but I could not get it to work. I turned to the solution to see how it was accomplished. I saw that it was done with a loop. By reviewing the code we're creating a function and writing a conditional for the divs_to_hide to display none. 
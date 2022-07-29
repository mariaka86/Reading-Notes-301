# Reading Notes
What is the single responsibility principle and how does it apply to components?
 SRP says that every module, class or function in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part.

 it applies to components since they have props and states

What does it mean to build a ‘static’ version of your application?

it means to have an mock application with no interactivity for modeling only.

Once you have a static application, what do you need to add?
components that reuse other components using props.

What are the three questions you can ask to determine if something is state?

- Is it passed in from a parent via props? If so, it probably isn’t state.

- Does it remain unchanged over time? If so, it probably isn’t state.

- Can you compute it based on any other state or props in your component? If so, it isn’t state.


How can you identify where state needs to live?
- by finding a common owner component


What is a “higher-order function”?
it's a function that operates on other function by either taking them as arguments or by returning them.

Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
 
return m in which the function m is greater than n

Explain how either map or reduce operates, with regards to higher-order functions.
 
 map loops over and takes in the value of the array depending on if it's greater than or less than ?
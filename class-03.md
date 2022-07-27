# Reading Notes
What does .map() return?
JSX elements

If I want to loop through an array and display each value in JSX, how do I do that in React?

using map()

Each list item needs a unique ____.

key

What is the purpose of a key?  

To help react identify which items have been added, changed or removed.

What is the spread operator?
a useful syntax for adding items to arrays, combining arrays or objects and spreading an array out into a function's arguments.

List 4 things that the spread operator can do.
- add items to lists
- combine objects
- convert nodelist to an array
- spread items out into an array

Give an example of using the spread operator to combine two arrays

const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩

Give an example of using the spread operator to add a new item to an array.

const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

Give an example of using the spread operator to combine two objects into one.

const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂

Videos
In the video, what is the first step that the developer does to pass functions between components?

In your own words, what does the increment function do?
 
increase the count by 1 everytime the array is looped over.

How can you pass a method from a parent component into a child component?

by utilizing state 

How does the child component invoke a method that was passed to it from a parent component?

by setting the state.







Reference: https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab

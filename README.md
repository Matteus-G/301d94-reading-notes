# 301d94-reading-notes
day 1

These topics matter because they all correspond with using react and bootstrap, which is a major focus to this course. 
Component-Based Architecture

What is a “component”?

Components are modular, portable replaceable and reusable sets of well defined functionality. 

What are the characteristics of a component?

Reusability, Replaceable, not Context specific, Extensible, Encapsulated and independent. They are meant to be reused in different situations in different apps, being reely substituted with similar components. They can be extended from existing components, and depicting the interfaces, allowing the caller to use its functionality, as well as having minimal dependencies on other components. 

What are the advantages of using component-based architecture?

It is easier to replace existing versions of the architecture with no impact on other components, making deployment less of a hassle, as well as reduced cost via third-party components. It becomes reusable and easily can modify the complexity via use of component containers and its Services. It is independent and easier to maintain and evolve the system. 

What is Props and How to Use it in React
props are arguments passed into react components, via HTML attributes 
What is “props” short for?

"Props" is short for properties

How are props used in React?

Properties are used to pass data from one component to another. 

What is the flow of props?

It is uni-directional, one way from parent to child. 



Day 2:

Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
Render will happen first
What is the very first thing to happen in the lifecycle of React?
Mounting, specifically getDerivedStateFromProps
Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

constructor,Render, componentDidMount, componentWillUnmount, react updates
What does componentDidMount do?
it is used ff you need to load anything using a network request or initialize the DOM
React State Vs Props

What kind of things can you pass into props?
Any value from another component in the component tree, as well as javascript data types
What is the big difference between props and state?
The state is a form of local storage to one specific component, and props are used to pass data from one to another. 
When do we re-render our application?
When the state changes in the parent component

What are some examples of things that we could store in state?
Strings, numbers, complex objects




Day 3
What does .map() return?
returns a map object after the original array has been ran through a function
If I want to loop through an array and display each value in JSX, how do I do that in React?
const listItems = numbers.map((number) =>
  <li>{number}</li>
Each list item needs a unique ____. 
Key
What is the purpose of a key?
Keys help react identift which items have changed, been removed or added. 
The Spread Operator

What is the spread operator?
It is a syntax that literally spreads an array into seperate arguments 
List 4 things that the spread operator can do.
It can copy arrays, combine them, USe math functions or even use an array as an argument. 
Give an example of using the spread operator to combine two arrays.
const hello = {hello: "😋😛😜🤪😝"}
const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}

const helloWorld = {...hello,...world}
console.log(helloWorld) // Object { hello: "😋😛😜🤪😝", world: "🙂🙃😉😊😇🥰😍🤩!" }

Give an example of using the spread operator to add a new item to an array.
a = {...a, ...theNewItemToAdd}; 
Object.assign(a, theNewItemsToAdd); 
Give an example of using the spread operator to combine two objects into one.

let person = {
  firstName: 'John',
  lastName: 'Doe',
  age: 25,
  ssn: '123-456-7890
};

let job = {
  jobTitle: 'Fry-Cook',
  location: 'McDonalds',
};

let employee = {
  ...person,
  ...job
};


Videos
How to Pass Functions Between Components

In the video, what is the first step that the developer does to pass functions between components?
In your own words, what does the increment function do?
How can you pass a method from a parent component into a child component?
How does the child component invoke a method that was passed to it from a parent component?





day 11

Fill in the chart below with five differences between SQL and NoSQL databases:

SQL	NoSQL
 	 SQL databases are vertically scalable while NoSQL databases are horizontaly scalable. SQL is tale based, NoSQL is document, key-value, graph or wide column stores. SQL databases are better for multi row transcactions, while NoSQL is better for unstructured data like docuuments or JSON
 	 
 	 
 	 
What kind of data is a good fit for an SQL database?
Give a real world example.
Keeping track of transaction history. 
What kind of data is a good fit a NoSQL database?
Give a real world example.
any sort of unsctructured data, like perhaps a UL?
Which type of database is best for hierarchical data storage?
NoSQL
Which type of database is best for scalability?
No SQL, just based on the graph bases. 
Videos
sql vs nosql (Video)

What does SQL stand for?

Structured Query Language
What is a relational database?
relational databases store and provides access to data points that are related to one another. 
What type of structure does a relational database work with?
What is a ‘schema’?
it is a list of logical structures of data. 
What is a NoSQL database?
they are non-tabular databases and store data differently than relational tables. 
How does it work?
it allows dev's to store unstrucutred data, giving them a lot of felxibility
What is inside of a Mongo database?
BSON docs? Just JSON data turned into a binary form, stored and quiered more effeciently. 
Which is more flexible - SQL or MongoDB? and why.
MongoDB is more dlexable and ensures high diverse data availability a SQL operates with the ACID properties, ensuring some greater reliability of transactions. 
What is the disadvantage of a NoSQL database?
it doesnt support ACID, and doesnt have reliability functions. 

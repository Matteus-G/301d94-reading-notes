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
If I want to loop through an array and display each value in JSX, how do I do that in React?
Each list item needs a unique ____.
What is the purpose of a key?
The Spread Operator

What is the spread operator?
List 4 things that the spread operator can do.
Give an example of using the spread operator to combine two arrays.
Give an example of using the spread operator to add a new item to an array.
Give an example of using the spread operator to combine two objects into one.
Videos
How to Pass Functions Between Components

In the video, what is the first step that the developer does to pass functions between components?
In your own words, what does the increment function do?
How can you pass a method from a parent component into a child component?
How does the child component invoke a method that was passed to it from a parent component?

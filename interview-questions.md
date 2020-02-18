# ASSESSMENT 2: Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own, there is always something more to learn.

1. What does CRUD stand for?

  Your answer: Create....  Read .... U..... Delete 
  <!--//almost got it :/-->

  Researched answer:CRUD is an acronym that stands for "Create, Read, Update and Delete".



2. What are the 5 HTTP verbs?

  Your answer: put patch and delete

  Researched answer: The primary or most-commonly-used HTTP verbs (or methods, as they are properly called) are POST, GET, PUT, PATCH, and DELETE. These correspond to create, read, update, and delete (or CRUD) operations, respectively.



3. When creating a basic (stateless) class component in React, what are the necessary elements needed to render "Hello World" on the page?

  Your answer: having a parent component passing down to its children?

  Researched answer: class Welcome extends React.Component {
  render()



4. What is JSX?

  Your answer: i honestly forgot

  Researched answer:JSX stands for JavaScript XML. With React, it's an extension for XML-like code for elements and components. Per the React docs and as you mentioned: JSX is a XML-like syntax extension to ECMAScript without any defined semantics.



5. What is the difference between React state and props?

  Your answer: state can modify any properties 

  Researched answer:In a React component, props are variables passed to it by its parent component. State on the other hand is still variables, but directly initialized and managed by the component. The state can be initialized by props.



6. STRETCH: What is hoisting in JavaScript?

  Your answer: i tried my best to remember 

  Researched answer:in JavaScript, a variable can be declared after it has been used



## Looking Ahead: Terms for Next Week

Research and define the following terms to the best of your ability.

- React lifecycle methodsEach component in React has a lifecycle which you can monitor and manipulate during its three main phases.

The three phases are: Mounting, Updating, and Unmounting.

Mounting
Mounting means putting elements into the DOM.

React has four built-in methods that gets called, in this order, when mounting a component:

constructor()
getDerivedStateFromProps()
render()
componentDidMount()
The render() method is required and will always be called, the others are optional and will be called if you define them.

constructor
The constructor() method is called before anything else, when the component is initiated, and it is the natural place to set up the initial state and other initial values.

The constructor() method is called with the props, as arguments, and you should always start by calling the super(props) before anything else, this will initiate the parent's constructor method and allows the component to inherit methods from its parent (React.Component).



- API An application programming interface is an interface or communication protocol between different parts of a computer program intended to simplify the implementation and maintenance of software. An API may be for a web-based system, operating system, database system, computer hardware, or software library.


- event.preventDefault() React uses synthetic events to handle events from button, input and form elements. ... It demonstrates how to add an item to a list by using a form element with input and button elements. In this case, a preventDefault is called on the event when submitting the form to prevent a browser reload/refresh
- 

- DOM events HTML DOM events allow JavaScript to register different event handlers on elements in an HTML document.

Events are normally used in combination with functions, and the function will not be executed before the event occurs (such as when a user clicks a button

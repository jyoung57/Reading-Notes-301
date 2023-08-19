> # Read: Class 02

## React Lifecycle

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

- Render

2. What is the very first thing to happen in the lifecycle of React?

- Mounting

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

- Constructor, render, React updates, componentDidMount, componentWillUnmount

4. What does componentDidMount do?

- This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount().

## React State Vs Props

1. What types of things can you pass in the props?

* We can pass any data type as props in React components: object, array, boolean, number, string, function, etc

2. What is the big difference between props and state?

* Props are used to pass data from a parent component to a child component, while state is used to manage data within a component.

3. When do we re-render our application?

* React components automatically re-render whenever there is a change in their state or props.

4. What are some examples of things that we could store in state?

* React components has a built-in state object. The state object is where you store property values that belong to the component. When the state object changes, the component re-renders.


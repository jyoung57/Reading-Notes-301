# Read: Class 04

> ## React - Docs: Forms

1. What is a ‘Controlled Component’?

* A component that is controlled by React state.

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

This is up to the users preference in what they need to update to do.  Both methods have their own drawbacks as where onSubmit can be delayed in state updating and may need to work more with a React lifecycle hook can be better to use for more complex forms.  Where onChange can be more real time and not require a callback function to update state but is not ideal for complex forms. 

3. How do we target what the user is entering if we have an event handler on an input field?

When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.

> ## The Conditional (Ternary) Operator Explained

1. Why would we use a ternary operator?

To simply or create a one line statement rather than making convoluted equations. 

2. Rewrite the following statement using a ternary statement:

````js
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
````
````jsx
x===y ? console.log(true) : console.log(false)
````

> ## Things I want to know more about
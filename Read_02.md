
Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

Render

What is the very first thing to happen in the lifecycle of React?

Mounting - phase

constructor() before mounting phase though which is weird   


Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
What does componentDidMount -This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount(). do?
Mounting -constructor render componentDidMount
Updating - React Updates  I geuss its not on the paper please have question that make more sense.  
Unmounting - componentWillUnmount

componentDidMount -This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount().

This article was not very helpful.

################################################################
What types of things can you pass in the props?
same things as you would with an arguement.  
initialization values 

What is the big difference between props and state?
Props are passed into a component 

State is handled inside that component -  its the current value that component is using 

When do we re-render our application?
- When we change the state 
- 
What are some examples of things that we could store in state?
- Counters or things with user input.  Forms 
-

What is the single responsibility principle and how does it apply to components?
 -  a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.
 
What does it mean to build a ‘static’ version of your application?
 -  Dont waste time adding in interactivity.  Just build a simple version get that connected then make it more complex 

Once you have a static application, what do you need to add?
-  Add state. 

What are the three questions you can ask to determine if something is state?
- Is it passed in from a parent via props? If so, it probably isn’t state.
- Does it remain unchanged over time? If so, it probably isn’t state.
- Can you compute it based on any other state or props in your component? If so, it isn’t state.


How can you identify where state needs to live?


For each piece of state in your application:
- Identify every component that renders something based on that state.
- ind a common owner component (a single component above all the components that need the state in the hierarchy).
- Either the common owner or another component higher up in the hierarchy should own the state.
- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.


###########################################################

What is a “higher-order function”?
- Functions that operate on other functions, either by taking them as arguments or by returning them
-   
Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
- Arrow syntax is weird but seems to return a direct evaluation   here m=11 n=arg=10 ==> T   it seems to set the arguements in 2 stages so just acts an overall template

Explain how either map or reduce operates, with regards to higher-order functions.
- it doesnt care about the data or the function it just looks for a true from the function and then maps it to a temp array then returns that array 

## React interview questions

1. What is state and props in reactjs?
   States are attributes of a component which store data which the page requires to run its functionalities.
   Props are states or data passed down to a child component.

2. What is high order component? How do you use it?

3. What is context? What are the benefits of it?
   Context is a method to pass data through components wihtout the need to pass props to child components. They can be interpreted similarly to global variables where React components can access wherever.
   The benefits of this method is that it eliminates the need to pass props to child components, elinimating redundancy.

4. How to assign and change the value of state in a component?
   Assigning states can be done through constructors within the class components and modifying them using a method called "setState".
   We can also use React hooks to assign and change values of states --> useState.

5. Could you explain the life-cycle of a react component?
   Life-cycle methods are used to free up resources taken when components are destroyed.
   e.g. componentDidMount() and componentWillUnmount()

6. What is fragment in react?
   Fragment allows the ability to return multiple elements without adding extra nodes to the DOM.

7. What is ref in react?
   Ref is used to indicate html tags within the render-side of the component. They can be used as access keys to point to the component of the html.

8. What is container component? What is presentational component?

9. How to pass a function to a component?
   html tags possess methods such as onclick which can be used to trigger a function. Functions can be declared outside the component itself and binded to the component to later then be called via the render tags of the component.

10. What is portal?
    A method to insert a child into a different location in the DOM.

11. How to share state between parent component and child component? How to share state between sibling components?
    States or data can be shared using props where the parent would pass the states as props to a child component.
    Callback functions can be passed also to manipulate the states from the parent component.
    Between siblings, we can do the same method however, this may be redundant use of code so we can install tools to help us control the states such as Redux.

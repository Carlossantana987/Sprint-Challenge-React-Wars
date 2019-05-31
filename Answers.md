# Answers

1.  What is React JS and what problems does it try and solve?

1a. React is a JavaScript library that trys to solve performance issues, from the DOM operations in the background , for applications with data that change over time at a high rate.

2.  What does it mean to _think_ in react?

2a. To think in react is breaking down a large application into smaller chunks called components that can be easily updated and managed.

3.  Briefly describe some of the differences between a Class/Stateful component and a Functional/Presentational component.

3a. A functional component is just a plain JavaScript function which accepts props as an argument and returns a React element. A class component requires you to extend from React.Component and create a render function which returns a React element. Class components manage and can pass there own state.

4.Describe state.

4a.state holds information about a component, state can be updated making the components "react".

5.Describe props.

5a. props is an {object} "property" or data that can be passed around as an argument to components. when passing state data from one component to another we use props.

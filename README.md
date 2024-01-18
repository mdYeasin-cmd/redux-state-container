# Redux State Container Learning Notes

### Covered topics in Module 01

- The nature of object is inherit someting from his parent object. Parent means from which class we extend the object.
- State only works inside React component
- If state change then DOM render again, it means re-render.
- Anti pattern means we should not follow that pattern.
- For one state we should use one useState, it the best practice
- If we want to use global state plain object is more beneficiall
- useReducer comes in React after redux invent. useReducer hooks inspired from redux.
- dispatch means to send something
- We keep the business logic of state management inside reducer function
- In createContext have two concept
  - provider
  - consumer
- In Redux have two version
  - React-Redux
  - Redux-Toolkit

### Covered topics in Module 02

- What is Redux?
  - Redux is a predictable state container for JavaScript Application.
- Advantages of use Redux
  - Predictable
  - Centralize
  - Debuggable
  - Flexible
- Terminology for Redux
  - Action
  - Dispatch
  - Payload
  - Reducer
  - Store
- By slice means that separation of concern
- For handle muteability, behind the schene Redux use immer package
- Hooks
  - useSelector hooks used for consume state
  - useDispatch hooks used for sent state to reducer
- Inside payload we can sent - number, string, array and object
- Immutability is the state where values are immutable (that is, not able to be changed). A value is immutable when altering it is impossible. Primitive data types are immutable, as we discussed above
- Function currying is a JavaScript concept
- In Redux we handle two types of state
  - Local State (Application State)
  - Server State
- RTK query is inpired from tanstack query
- RTK query used for server data fetching

### Covered topics in Module 03

- What is Compound Component?
  - Component composition is a fundamental concept in React that allows us to build complex UIs by combining smaller, independent components. It promotes code reusability, makes our code more readable, and allows us to better manage our application's state and behavior.
  - Compound components are a pattern in React, where several components are used together such that they share an implicit state that allows them to communicate with each other in the background.
- What is Nested Component?
  - Nested components in ReactJS refer to the components that are defined inside another component. In other words, a component can contain other components as its children, and these child components can, in turn, contain other components, creating a hierarchical structure of components.
- When we use Redux Toolkit, we can use push array method cause immuteability handle by Redux Toolkit behind the schene.
- In Redux Toolkit for CRUD operation have two terms
  1. Query
  - It means ask something to databse and get answer.
  - GET method in Redux Toolkit called query
  2. Mutation
  - PUT, PATCH, DELETE all are called mutation in Redux Toolkit

### Covered topics in Module 04

- Redux have built-in cache feature
- For use cache feaature we need
  - tagTypes --> Need inside createApi
  - providesTags --> Need inside query
  - invalidatesTags --> Need inside mutation
- In api Query Hooks second parameter, we can pass different options
- When we need live interaction like relaod after 30 seconds, we can use polling interval options
- By keep cache we can increase the web site performance

### Covered topics in Module 05

- When we use Framework or Library we should avoid writing raw css code.
- We should analysis requirements before jump into code.
- "/" by slash means that the router path is Absolute path.
- Without slash router path is Relative path.
- Need to think always how make the code reuseable with more flexible way.
- DRY -> Don't Repeat Yourself

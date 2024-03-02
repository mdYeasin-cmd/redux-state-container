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

### Covered topics in Module 06

- "!" --> Not null assertion operator in typescript. By this we mean that the value will not undefined or null
- What is Barrel?
  - Barrels are a technique used to roll up exports from different modules into a single one, usually called index.ts, to simplify the imports. Barrels thus simply combine the exports of one or more other modules. By making use of the re-export functionality, you can actually create barrels.
- What is HOC - Higher Order Component?
  - In React, a higher-order component is a function that takes a component as an argument and returns a new component that wraps the original component.
- In Redux RTK query for createApi() function three arguments are mandatory
  1. reducerPath: "name",
  2. baseQuery: fetchBaseQuery({})
  3. endpoints: () => ({})
- Steps of set cookie in browser with Redux
  1. In baseApi fetchQuery credentials option should be "include"
  2. On backend in cors credentials should be true
- Authentication related package name
  - jwt-decode
  - redux-presist
- Serializeable object and Non-serializeable object
  - A serializable object can be converted into some other representation such as text in order to be easily transmitted across process boundaries while a non-serializable object cannot.
  - Serializeable object we can stringify esily using JSON.stringify() method.
  - Which object we can not strinify using JSON.stringify() method that is non-serializeable object in JavaScript
  - In other word if object contian method that is non-serializeable object

### Covered topics in Module 07

- Login Redirect and Logout
- Send refresh token to get acess token
- If refresh token is expired kick out user
- Form handle npm
  - react-hook-form
  - Formik
- For catch jwt.verify() fuction error, we should use it inside try catch block.

## Fullstack Track

### Covered topics in Module 10

- When we work in a development team, before start coding we should pull from github reposity.
- If we organize our folder structure depending on routes name that will more navigateable on developer perspective

### Covered topics in Module 11

- FormData() constructor used for send file and form data to backend.
- Some method to see form data value -
  - formData.get("key", "value");
  - formData.entries();
  - Object.formEntries(formData) --> this is the best option for see form data values.
- Image uplaod functionality don't work in free hosting server

### Covered topics in Module 12

- Need to study with modal ux.
- Andt table pagination is not good, because we can't implement backend pagination there. Instead of table pagination we can use Pagination component fron Andt where we can implement backend pagination.

### Covered topics in Module 13

- Object.values() method is handful for manipulate object in differnet cases.

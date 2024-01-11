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

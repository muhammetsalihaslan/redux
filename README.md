# REDUX 
        **********WHAT İS REDUX**********

its an open source state managemenr library

which is help us to manage the complex states

simple structure of redux

install library redux toolkit and react-redux

code:
  
$ yarn add @reduxjs/toolkit react-redux

multiple store are not reccommenden by creater of redux

createSlice :: A function that accepts an initial state, an object of reducer functions, and a "slice name", and automatically generates action creators and action types that correspond to the reducers and state.


createStore :: A friendly abstraction over the standard Redux createStore function

useSelector/useDispatch::useSelector and useDispatch are a set of hooks to use as alternatives to the existing connect() higher-order component. The equivalent of map state to props is useSelector. It takes in a function argument that returns the part of the state that you want. The equivalent of map dispatch to props is useDispatch. We can invoke useDispatch and store it to a variable, dispatch. Dispatch will work with the allActions imported from the actions folder.
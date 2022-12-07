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


we have to export both our actions and reducers :: counterSlice actions: increment decrement reducers: counterSlice.reducer;

in this tutorial so redux store.js is main thing we have to import our action part

        *********STRUCTURE**********


Redux part:: main component is store inside of app folder we have to import our redux in here and write our calling function inside of reducers
other component:: counterSlice is our action of what we want with redux 
Counter.js:: ui part we use useselector and usedispatch for using redux useSelector for select our redux action usedispatch for use our redux action 

all of them have to in index.js part we create them with provide and store 

and app.js part we add counter in it 

(a && b) does not even evaluate b if a is falsy and returns a straight away; but if a is truthy, the it evaluates and returns b

(a || b) does not even evaluate b if a is truthy and returns a, but if it's falsy, then it evaluates and returns b

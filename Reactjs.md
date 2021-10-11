# 23 -08- 2021 Reactjs udemy course
A javascript library for building user interfaces.
- A client side javascript library.
- All about building modern react user interfaces for web.
- declarative, component-focussed approach
# JavaScript 
## variable
- To reassign a variable use "let", if not use "const"
## Functions
- Normal Function
```
function square(number){
  return number * number;
}
square(2);
```
- Arrow Function
```
const square = (numer) => {
    return number*2;
}
console.log(square(2));
```
## Export and Import
1. default export (we can give any name)
     -  import name from './filename.js' (or)
     -  import nme from './filename.js'
2. named export (we have mention same name)
     - import {name} from './filename.js (or) [have to call exact name]
     - import {name as NME} from './filename.js (or) [We can use aliase to choose name]
## Classes
      Classes are just blueprints for javascript object
1. Classes have both methods and properties
     - Methods - simply function attached to the classes
     - Properties - variables attached to the classes
## Spread and Rest operator
1. Used to split up an array or obejct (or) expand an array or object
2. Used to merge functions into a array (or) Functions to get the parameter or the may be the resi of the parameter
## Destructuring
     Pulling out an element in an array or properties.
- Easily extract an element in an array or object and store them in a variable.
```
const num = [1,2,3]
[N1,N2] = num [ will print => 1,2]
[N1, , N3] = num [ will print => 1,3]
```
## References and primitive variable
  - Numbers, Strings and Booleans are primitive types
  - The copy of value object array are reference types
```
const num = 45
const num1 = num [num1 Will print => 45]
```
```
const person = {
     name = 'keerthu'
} 
const secondPerson = person [ will print => vijayabalaje not keerthu]
person.name = 'vijayabalaje' 
```
To avaid this we have to create new object
```
const person = {
     name = 'keerthu'
} 
const secondPerson = {
     ...person 
} [will print => keerthu]
person.name = 'vijayabalaje'
```
# React Basics
 - Reusable and reactive components consisting of HTML, Javascript(CSS)
> npx create-react-app my-app (or) npx create-react-app 'name specify'

To open application in browser, enter
>  npm start 
To terminate project 
> enter control c

- Step 1 - remove everything and keep app.js, index.js, index.css
## Components
1. A component in react is just a javascript function.


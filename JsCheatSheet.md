###JavaScript Cheat Sheet

```js
typeof (
  // to get the type of the variable
  console.log(typeof exmapleVar)
)
```

[Operator Precedence](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence)

[JavaScriptEvents](https://developer.mozilla.org/en-US/docs/Web/Events)

```js
/*
Falsy Values
undefined
null
0
''
NaN

Truthy Values
all values which are not falsy
*/

//Array mutationṭ
var name = ['John', 'Mark', 'Jane']

name[name.length] = 'Mary' //adds an element

name[0] = 'Doe' //Array mutation

name.push('example') //adds an element end of an array
name.unshift('example') //add an element at the begining of an array
name.pop() //removes the element in the end of an array.
name.shift() //removes first element in the array.
name.index('example') // will the return the position of an elemnt of the array we pass, else return -1.
```

Next Gen JS
```js
let //variable value

const // constant value

//Arrow Function
const myFunc = () => {
  //code here
}

//JSX supports Export and Import

//person.js
const person = {
  name='Max';
}
export default person

//utility.js
export const clean = () => {....}
export const baseData = 10;

//app.js
import peron from './person.js'
import {baseData} from './utility.js'
import {clean} from './utility.js'

import {baseData, clean} from './utility.js'

import {baseData as data} from './utility.js'

import * as bundled from './utility.js'

//Spread or Rest operator
...

const number = [1, 2, 3, 4]
const newNumbers = [...number, 5, 6];

//Destrucing
const number = [1, 2, 3];
[num1, num2] = numbers;
console.log(num1, num2);

//Array funtiions - numbers.map
const numbers = [1, 2, 3];
const doubleNumArray = numbers.map((num) => {
  return num * 2;
});

find();

findIndex();

filter();

reduce();

concat();

slice();

splice();
```

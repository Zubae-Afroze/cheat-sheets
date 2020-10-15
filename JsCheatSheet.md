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

## Variables
A symbolic container, called a variable because its value can vary over time as needed.

Static typing or type enformecement is when you declare the variable type, such as String or Number so they can't hold values beyond its type definition.

Weak typing or dynamic typing is when a variable can hold any type of value at any time.

JavaScript uses dynamic typing.

### Declaring a variable in JavaScript
To declare a JavaScript variable, use the `var` keyword:
```js
var name = 'Rodrigo Reis';

console.log(name); // prints 'Rodrigo Reis' to the console
```

<!--- Writte examples of explicity and implicitly coersion like: console.log( String( my_variable ) ) --->

```
The main purpose of variables is to manage program state.
```

### Constants
Constants are used generally at the beginning of the program to define values that you don't want to change throughout the program.
By convention, constants are usually capitalized, with underscores `_` between multiple words.

### Declaring a constant in JavaScript
To declare a JavaScript constant, use the `const` keyword:
```js
const TAX_RATE = 0.08;	// 8% sales tax

var amount = 99.99;

amount = amount * 2;

amount = amount + (amount * TAX_RATE);

console.log( amount );              // 215.9784
console.log( amount.toFixed( 2 ) ); // "215.98"
```

## Blocks
JavaScript blocks serve to group a series of statements together.

To group statements using JavaScript, just use a curly-brace pair `{...}`.

The below code uses blocks to group statements:
```js
{
  let URL = 'https://www.google.com';
  console.log(URL);
}
```

Generally, you don't see this kind of standalone grouping blocks.
A common block is seen in the below code:
```js
let status = true;

if (status) { console.log('The status is set to: ' + status); } // <- the block is attached to the if statement
```

### Conditionals

1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```
// Ans - The difference between the two `sum` function is first `sum` function returns the value the output will be `sum` of a + b. and second `sum` function console.log the value and output will be undefined..

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

// Ans -  the value of `first` will be `sum` of (a + b). and the value of `second` will be undefined.

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

// Ans - the output will be when we call `sum` function (first) with three parameter like `sum (12, 24,35)` will be 36.. the reason is we return the value of two parameter a + b.

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

// Ans - Yes we can store the first `sum` in a variable named `add`. because 
Functions stored in variables do not need function names. They are always invoked (called) using the variable name.

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

// Ans - function sayHello (name) {
  return `Hello ${name}`
}

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
// Ans - 'Hello, John';

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';
function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // `john`

showMessage(); // 'Hello, John'

alert(userName); // `john`
```

8. What is a Anonymous Function give example of three functions.

// Ans - an anonymous function is that type of function that has no name or we can say which is without any name.

let addNumbers = function (numA, numB) {
  return numA + numB;
}

9. Can function declaration be a Anonymous Function? Explain

// Ans - The main difference between a function expression and a function declaration is the function name, which can be omitted in function expressions to create anonymous functions.

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
// Ans - (1) function getName(dogName, ownerName) { 
  return '${dogName} ${ownerName}';
}
(2) function fullName (firstName, lastName) {
  return `${firstName} ${lastName};
}
(3) function subtractTwoNumbers(a, b) {
  return a - b;
}
(4) function addTwoNumbers (num1,num2) {
  return num1 + num2;
}
(5) function getSqare (number) {
  return num * num;
}
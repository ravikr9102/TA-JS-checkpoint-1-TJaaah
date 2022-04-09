1. Using loops take 10 inputs from user and find the average of all the numbers.
// Ans - let sum = 0;
for (let i = 0; i <= 10; i ++) {
  let number = +prompt(`Enter number`);
  sum = sum + number;
}
let average = sum / 10;

2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
```
// Ans - println is not defined

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.

// Ans - function getEven (max) {
  return (max * (max + 1));
}
getEven (10);

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.

// Ans - function getOddSum (max) {
  return max * max;
}
getOddSum (10);

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

// Ans - function getProductOfDigits (num){
  if(num < 0 ) {
    return `not a valid input`;
  }
  else {
    let p = 1;
  while (num > 0) {
    remainder = num % 10;
    p = p * remainder;
    num = Math.floor (num / 10);
  }
  return p;
  }
}

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // 'Bigger than 5'
check(1); // 'Smaller than 5'
check(5); // 5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // 'You are arya'
getOutput('John'); // 'You are john'
getOutput(); // 'Who are you'
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // You are arya
'Who are you'
getOutput('John'); // You are john
'Who are you'
getOutput(); // 'Who are you'
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
// Ans - Yes a function have multiple return statement if possible more than one function nested..

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
// Ans - The difference between `for` loop and while loop is that in for loop the number of iterations to be done is already known and is used to obtain a certain result whereas in `while` loop the command runs until a certain condition is reached and the statement is proved to be false.

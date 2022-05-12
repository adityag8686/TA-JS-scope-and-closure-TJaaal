1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let percentage = (marks,total) =>{
    return (marks * 100) / total;
}
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
let percentage = (marks,total) =>{
    return (marks * 100) / total;
}
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
let percentage = (marks, total) => {
  return (marks * 100) / total;
};

```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
function percentage (marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
function percentage (marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => (marks * 100) / total;
function (marks, total) {
  return (marks * 100) / total;
};
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
because function gives a reseult or value and anything that act as a value can be defined as expression

let marks = (marks1, marks2) => marks1+marks2;

4. Why is a function call an expression in JavaScript?
because it gives a result which can be a value or an expression 

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer true
five = add; // Answer invalid
five = five(10, 11); // Answinvalider
five = function () {
  return 'Hello';
}; // Answer hello
```

6. What is the difference between function definition and function call? Explain with an example.
function add(a, b) {
  return a + b;
}
add(2, 3)
7. What is the similarities between function definition and function call?

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid or invalid
code is invalid as first is a function which will only execute when it is called whereas the second one stores the value of a hello function which has user as variable which is not available
```

9. What is higher order function explain with an example.
a function which accepts a fiunction or return a function is higher order function

10. Explain what is callback function. Why you can pass a function inside a function?
calling a function from another function is call back function
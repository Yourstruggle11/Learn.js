# Learn.js

## Topic: Execution Context - Solutions

In this section, you'll find solutions to the exercises related to Execution Context in JavaScript.

### Exercise 1: Variable Declaration
**Solution:**

```javascript
// Declare the variable 'message'
const message = "Hello, JavaScript!";

// Log the value of 'message' to the console
console.log(message);
```

###  Explanation:
Variables are stored in the memory component of the execution context. In this exercise, we declared a variable called message and assigned it the value "Hello, JavaScript!". We then logged the value of message to the console.

### Exercise 1: Function Execution

**Solution:**
```javascript
// Define the 'addNumbers' function
function addNumbers(num1, num2) {
  return num1 + num2;
}

// Call the function with different sets of numbers
const result1 = addNumbers(5, 7);
const result2 = addNumbers(10, 20);

// Log the results to the console
console.log(result1); // Output: 12
console.log(result2); // Output: 30
```

### Explanation: 
JavaScript executes functions in the code component of the execution context. In this exercise, we defined a function addNumbers that takes two parameters and returns their sum. We called this function with different sets of numbers and logged the results to the console.

### Exercise 1: Variable Scope

**Solution:**
```javascript
// Declare a global variable
const globalVar = "I'm global";

// Define a function
function exampleFunction() {
  // Declare a local variable
  const localVar = "I'm local";
  
  // Log both global and local variables
  console.log(globalVar); // Output: "I'm global"
  console.log(localVar);  // Output: "I'm local"
}

// Call the function
exampleFunction();
```
### Explanation: 
Variables have scope within the execution context. In this exercise, we declared a global variable globalVar and a local variable localVar inside the exampleFunction. We logged both global and local variables to the console from within the function, demonstrating variable scope.

### Exercise 1: Asynchronous Callback
**Solution:**
```javascript
// Define the 'delayedGreeting' function with a callback
function delayedGreeting(callback) {
  setTimeout(callback, 2000);
}

// Callback function
function greet() {
  console.log("Hello after 2 seconds!");
}

// Call 'delayedGreeting' with the 'greet' callback
delayedGreeting(greet);
```
### Explanation:
JavaScript can handle asynchronous operations using execution context. In this exercise, we defined a function delayedGreeting that takes a callback function and uses setTimeout to delay the execution of the callback by 2 seconds. We called delayedGreeting with the greet callback, resulting in "Hello after 2 seconds!" being logged to the console.

### Exercise 1: Execution Order
**Solution:**
```javascript
// Define three functions
function first() {
  console.log("First function");
}

function second() {
  console.log("Second function");
}

function third() {
  console.log("Third function");
}

// Call the functions in a specific order
first();
second();
third();
```
### Explanation:
 JavaScript maintains a specific synchronous order of execution for function calls. In this exercise, we defined three functions (`first`, `second`, and `third`) and called them in a specific order. The output reflects the order of execution, demonstrating the synchronous nature of JavaScript.

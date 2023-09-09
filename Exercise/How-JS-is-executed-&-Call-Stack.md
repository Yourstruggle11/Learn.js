# Learn.js

## Topic: How JS is Executed & Call Stack

In this section, we will explore how JavaScript is executed and the role of the Call Stack in managing execution contexts.

### Exercise 1: Memory Creation Phase

**Problem:** Consider the following JavaScript code snippet:
```javascript
var x = 10;
function greet(name) {
  console.log("Hello, " + name + "!");
}
var y = 20;
```
Explain the memory creation phase for this code. Describe which variables and functions are allocated memory and their initial values.

**Instructions:**

- Analyze the code provided and explain the memory creation phase.
- List the variables and functions that are allocated memory during this phase.
- Describe the initial values (if any) assigned to these variables and functions.

### Exercise 2:  Function Execution Context

**Problem:** Consider the following JavaScript code snippet:
```javascript
function calculateSum(a, b) {
  var result = a + b;
  return result;
}
var total = calculateSum(5, 7);
```
Explain the creation and execution of the function execution context for the calculateSum function when it is called with arguments 5 and 7.

**Instructions:**

- Describe the steps involved in creating a new execution context for the calculateSum function.
- Explain what happens during the memory creation phase and code execution phase of this execution context.
- Clarify how the function's return value is calculated and returned to the global context.

### Exercise 3: Call Stack Operations

**Problem:** Given the following JavaScript code:
```javascript
function first() {
  console.log("First function");
}

function second() {
  first();
  console.log("Second function");
}

second();
```

Explain the operations of the Call Stack during the execution of the second function and its interaction with the `first` function.

**Instructions:**

- Describe the order in which execution contexts are added to the Call Stack as the code is executed.
- Explain how the Call Stack manages the execution of functions and their return values.
- Provide a step-by-step explanation of the Call Stack's operations throughout the code execution.

### Exercise 4: Global Execution Context Deletion

**Problem:** Given the JavaScript code snippet:
```javascript
function a() {
  console.log("Function 'a'");
}

function b() {
  a();
  console.log("Function 'b'");
}

b();
```
Explain the process of global execution context deletion and the order in which execution contexts are removed from the Call Stack.

**Instructions:**

- Describe how the execution contexts for functions a and b are added to the Call Stack.
- Explain the sequence of operations when functions are called and returned.
- Provide a clear explanation of how the global execution context is deleted.
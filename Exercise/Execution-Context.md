# Learn.js

## Topic: Execution Context

In this section, we will explore the concept of Execution Context in JavaScript through practical code examples. Execution context is essential to understand how JavaScript code is executed.

### Exercise 1: Variable Declaration

**Problem:** Declare a variable called `message` and assign the string "Hello, JavaScript!" to it. Log the value of `message` to the console.

**Instructions:**
- Write JavaScript code to complete the task described in the problem statement.
- After writing the code, explain how variables are stored in the memory component of the execution context.

### Exercise 2: Function Execution

**Problem:** Create a function called `addNumbers` that takes two parameters, `num1` and `num2`, and returns their sum. Call this function with different sets of numbers and log the results to the console.

**Instructions:**
- Define the `addNumbers` function and write code to return the sum of `num1` and `num2`.
- Call the `addNumbers` function with different sets of numbers and log the results to the console.
- Explain how the code component of the execution context executes functions line by line.

### Exercise 3: Variable Scope

**Problem:** Declare a variable called `globalVar` outside of any functions. Inside a function, declare a variable called `localVar`. Try to log both `globalVar` and `localVar` from within the function. What happens, and why?

**Instructions:**
- Declare a global variable `globalVar` outside of any functions.
- Define a function `exampleFunction` and declare a local variable `localVar` inside it.
- Inside `exampleFunction`, log both `globalVar` and `localVar`.
- Call `exampleFunction` and observe the output.
- Explain the concept of variable scope and how global and local variables interact within the execution context.

### Exercise 4: Asynchronous Callback

**Problem:** Create a function called `delayedGreeting` that takes a callback function as a parameter. Inside `delayedGreeting`, use `setTimeout` to delay the execution of the callback by 2 seconds. Call `delayedGreeting` with a callback function that logs "Hello after 2 seconds!".

**Instructions:**
- Define the `delayedGreeting` function with a callback parameter.
- Inside `delayedGreeting`, use `setTimeout` to delay the execution of the callback by 2 seconds.
- Create a callback function that logs "Hello after 2 seconds!"
- Call `delayedGreeting` with the callback function.
- Explain how JavaScript handles asynchronous operations within its single-threaded nature and the role of execution context in managing callbacks.

### Exercise 5: Execution Order

**Problem:** Write a JavaScript program that includes three functions: `first`, `second`, and `third`. Each function logs its name to the console. Call these functions in a specific order (e.g., `first()`, `second()`, `third()`) and observe the order of execution.

**Instructions:**
- Define three functions: `first`, `second`, and `third`, each logging its name to the console.
- Call the functions in a specific order (e.g., `first()`, `second()`, `third()`).
- Observe and explain how JavaScript maintains a specific synchronous order of execution for function calls.

These exercises provide practical examples to help you understand execution context concepts in JavaScript. Follow the instructions for each exercise to practice and gain a better understanding of execution context.

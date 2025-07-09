
## Introduction

In this lesson, we will explore **basic conditions** in JavaScript—how to compare values using equality (`==`) and relational (`>`, `<`, `>=`, `<=`) operators. This is essential for understanding how **programs make decisions** based on data.

## Learning Objectives

By the end of this lesson, you will be able to:

- Understand how to compare values using equality and relational operators.
- Write simple conditional expressions in JavaScript.
- Use `console.log()` to view the output of condition evaluations.

## Theory

### What are Basic Conditions?

In programming, a **condition** is an expression that evaluates to either `true` or `false`. These boolean results are used to control the **flow of a program**, especially with `if` statements and loops.

To compare values, JavaScript provides **comparison operators**:

| Operator | Description           | Example  | Result  |
| -------- | --------------------- | -------- | ------- |
| `==`     | Equal to              | `5 == 5` | `true`  |
| `!=`     | Not equal to          | `5 != 5` | `false` |
| `>`      | Greater than          | `10 > 5` | `true`  |
| `<`      | Less than             | `3 < 7`  | `true`  |
| `>=`     | Greater than or equal | `5 >= 5` | `true`  |
| `<=`     | Less than or equal    | `4 <= 2` | `false` |

### Analogy

Think of conditions like **yes/no questions** you ask:

- "Is the temperature more than 30°C?" → Yes or No → `true` or `false`
- "Is 10 equal to 10?" → `true`
- "Is 7 greater than 15?" → `false`

In JavaScript, comparison operators help us ask and answer these kinds of questions.

### Why are Conditions Important?

Conditions allow a program to make **decisions**. Without them, software would be static and unable to adapt to different inputs or situations. They are fundamental to:

- Running code only when something is true (using `if`)
- Loops (like `while` or `for`) that depend on a condition
- Validating user input
- Controlling program flow

## Hands-On Coding

### Writing Your First Condition Check

Let’s explore how to compare values using JavaScript and view the results using `console.log()`.

```javascript
// Using equality (==)
console.log(5 == 5);     // true
// Greater than
console.log(10 > 5);       // true

// Less than or equal to
console.log(4 <= 2);       // false

// Not equal (!=)
console.log(5 != 5);     // false
```

Each line outputs `true` or `false` to the console, helping us understand what the condition evaluates to.

### Using Conditions in a Program

```javascript
let age = 18;

if (age >= 18) {
    console.log("You are eligible to vote.");
} else {
    console.log("You are not eligible to vote.");
}
```

This program checks if a person is 18 or older and prints the appropriate message.

## Exercises

Now it's your turn! Try the following exercises to reinforce your understanding:

1. Write a condition that checks if `10` is equal to `'10'` using `==`.
2. Create a program that checks if a number is positive, negative, or zero.
3. Write a program that takes a user's score and prints:
   - `"Excellent"` if the score is above 90
   - `"Good"` if the score is between 70 and 90
   - `"Needs Improvement"` if the score is below 70


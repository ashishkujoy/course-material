
### 📘 Overview

An **expression** in JavaScript is **any piece of code that evaluates to a value**.

> A number like `5` is a value.  
> An expression like `5 + 2` evaluates to another value — `7`.

Arithmetic expressions use **numbers** and **operators** to compute a **numeric result**.

---

## 🧠 What is an Expression?

In JavaScript:

> An **expression** is **any valid unit of code that resolves to a value**.

Examples:

```javascript
42
3 + 5
3 * 4
```

## Arithmetic Operators

| Operator            | Symbol | Example  | Result |
| ------------------- | ------ | -------- | ------ |
| Addition            | `+`    | `4 + 3`  | `7`    |
| Subtraction         | `-`    | `10 - 2` | `8`    |
| Multiplication      | `*`    | `6 * 2`  | `12`   |
| Division            | `/`    | `20 / 4` | `5`    |
| Modulus (Remainder) | `%`    | `10 % 3` | `1`    |

## Operator Precedence

JavaScript follows **BODMAS/PEMDAS** rules for order of operations:

```javascript
2 + 3 * 4    // 14 (Multiplication happens first)
(2 + 3) * 4  // 20 (Parentheses change the order)
```

Use `()` to **group expressions** and control evaluation.
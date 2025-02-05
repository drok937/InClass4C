Introduction to Conditionals and Boolean Logic
==============================================

Conditionals allow programs to make decisions based on specific conditions. These decisions are made using **boolean logic**, which evaluates expressions to `true` or `false`.

Boolean Values
--------------

In JavaScript, a boolean value is either `true` or `false`:

```javascript
let isRaining = true;
let isSunny = false;
```

If Statements
-------------

An `if` statement executes a block of code if the condition inside the parentheses evaluates to `true`:
```javascript
let temperature = 30;
if (temperature > 25) { 
    console.log("It's a warm day!"); 
}
```
If-Else Statements
------------------

The `else` block executes if the condition is `false`:
```javascript
let isHungry = false;
if (isHungry) {
    console.log("Time to eat!");
} else {
    console.log("Not hungry right now.");
}
```
Else-If Statements
------------------

Use `else if` to check multiple conditions:
```javascript
let score = 85;
if (score >= 90) {
    console.log("Grade: A");
} else if (score >= 80) {
    console.log("Grade: B");
} else {
    console.log("Keep trying!");
}
```
Logical Operators
-----------------

Logical operators help combine multiple conditions:

`&&` (AND) - Both conditions must be true.
```javascript
if (isRaining && temperature < 20) {
    console.log("Wear a jacket.");
}
```
`||` (OR) - At least one condition must be true.
```javascript
if (isRaining || isSunny) {
    console.log("Weather is changing.");
}
```
`!` (NOT) - Reverses a boolean value.
```javascript
if (!isHungry) {
    console.log("You are not hungry.");
}
```
Conclusion
----------

Conditionals and boolean logic are essential for controlling program flow. Understanding these concepts allows developers to create dynamic and interactive applications.
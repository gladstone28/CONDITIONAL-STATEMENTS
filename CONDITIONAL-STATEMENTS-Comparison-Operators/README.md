[Lesson link](https://www.codecademy.com/paths/build-web-apps-with-react/tracks/bwa-javascript-functions-arrays-and-loops/modules/learn-javascript-control-flow/lessons/control-flow/exercises/comparison-operators)

### CONDITIONAL STATEMENTS

**Comparison Operators**


When writing conditional statements, sometimes we need to use different types of operators to compare values. These operators are called comparison operators.

Here is a list of some handy comparison operators and their syntax:

- Less than: <
- Greater than: >
- Less than or equal to: <=
- Greater than or equal to: >=
- Is equal to: ===
- Is not equal to: !==

Comparison operators compare the value on the left with the value on the right. For instance:

```
10 < 12 // Evaluates to true

```
It can be helpful to think of comparison statements as questions. When the answer is “yes”, the statement evaluates to true, and when the answer is “no”, the statement evaluates to false. The code above would be asking: is 10 less than 12? Yes! So 10 < 12 evaluates to true.

We can also use comparison operators on different data types like strings:
```
'apples' === 'oranges' // false
```
In the example above, we’re using the identity operator (===) to check if the string 'apples' is the same as the string 'oranges'. Since the two strings are not the same, the comparison statement evaluates to false.

All comparison statements evaluate to either true or false and are made up of:

- Two values that will be compared.
- An operator that separates the values and compares them accordingly (>, <, <=,>=,===,!==).

Let’s practice using these comparison operators!

### Instructions

Checkpoint 1 Passed

1. Using let, create a variable named hungerLevel and set it equal to 7.

Checkpoint 2 Passed

2. Write an if...else statement using a comparison operator. The condition should check if hungerLevel is greater than 7. If so, the conditional statement should log, 'Time to eat!'. Otherwise, it should log 'We can eat later!'.

After you press run, play around with the condition by tweaking the comparison of hungerLevel by using different operators such as <=,>=,>, and <.

The syntax for an if...else statement is:
```
if (condition) {
  // Execute this code
} else {
  // Execute this code
}

```

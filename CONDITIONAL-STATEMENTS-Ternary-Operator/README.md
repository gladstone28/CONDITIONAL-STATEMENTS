[lesson link](https://www.codecademy.com/paths/build-web-apps-with-react/tracks/bwa-javascript-functions-arrays-and-loops/modules/learn-javascript-control-flow/lessons/control-flow/exercises/ternary-operator)

### CONDITIONAL STATEMENTS

**Ternary Operator**

In the spirit of using short-hand syntax, we can use a ternary operator to simplify an if...else statement.

Take a look at the if...else statement example:
```
let isNightTime = true;

if (isNightTime) {
  console.log('Turn on the lights!');
} else {
  console.log('Turn off the lights!');
}
```
We can use a ternary operator to perform the same functionality:
```
isNightTime ? console.log('Turn on the lights!') : console.log('Turn off the lights!');
```
In the example above:

- The condition, isNightTime, is provided before the ?.
- Two expressions follow the ? and are separated by a colon :.
- If the condition evaluates to true, the first expression executes.
- If the condition evaluates to false, the second expression executes.

Like if...else statements, ternary operators can be used for conditions which evaluate to true or false.


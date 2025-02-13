[Lesson link](https://www.codecademy.com/paths/build-web-apps-with-react/tracks/bwa-javascript-functions-arrays-and-loops/modules/learn-javascript-control-flow/lessons/control-flow/exercises/truthy-falsy-operators)


### CONDITIONAL STATEMENTS

**Truthy and Falsy Assignment**

Truthy and falsy evaluations open a world of short-hand possibilities!

Say you have a website and want to take a user’s username to make a personalized greeting. Sometimes, the user does not have an account, making the username variable falsy. The code below checks if username is defined and assigns a default string if it is not:
```
let username = '';
let defaultName;

if (username) {
  defaultName = username;
} else {
  defaultName = 'Stranger';
}

console.log(defaultName); // Prints: Stranger
```
If you combine your knowledge of logical operators you can use a short-hand for the code above. In a boolean condition, JavaScript assigns the truthy value to a variable if you use the || operator in your assignment:
```
let username = '';
let defaultName = username || 'Stranger';

console.log(defaultName); // Prints: Stranger
```
Because || or [statements](https://www.codecademy.com/resources/docs/javascript/statements) check the left-hand condition first, the variable defaultName will be assigned the actual value of username if it is truthy, and it will be assigned the value of 'Stranger' if username is falsy. This concept is also referred to as short-circuit evaluation.


### Instructions

Checkpoint 1 Passed
1. Let’s use short-circuit evaluation to assign a value to writingUtensil. Do not edit tool yet, we’ll return to tool in the next step.

Assign to writingUtensil the value of tool and if tool is falsy, assign a default value of 'pen'.

Make sure you’re assigning tool before 'pen'. You will be using the || operator to short-circuit evaluate. For example:

let newVar = anotherVar || 'default value'

Checkpoint 2 Passed

2. Notice that text 'The pen is mightier than the sword' logged to the console. Which means the value of writingUtensil is 'pen'.

What if we reassign the value of tool to 'marker'. Let’s see what happens to the value of writingUtensil.

Since we reassign tool to a non-empty string, the value of writingUtensil becomes 'marker' and 'The marker is mightier than the sword' is logged to the console.


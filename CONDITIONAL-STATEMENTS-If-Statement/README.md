[Link to the lesson on if statements](https://www.codecademy.com/paths/build-web-apps-with-react/tracks/bwa-javascript-functions-arrays-and-loops/modules/learn-javascript-control-flow/lessons/control-flow/exercises/if-statement)

### CONDITIONAL STATEMENTS

**If Statement**

We often perform a task based on a condition. For example, if the weather is nice today, then we will go outside. If the alarm clock rings, then we’ll shut it off. If we’re tired, then we’ll go to sleep.

In programming, we can also perform a task based on a condition using an if statement:
```
if (true) {
  console.log('This message will print!'); 
}
// Prints: This message will print!
```
Notice in the example above, we have an if statement. The if statement is composed of:

- The if keyword followed by a set of parentheses () which is followed by a code block, or block statement, indicated by a set of curly braces {}.
- Inside the parentheses (), a condition is provided that evaluates to true or false.
- If the condition evaluates to true, the code inside the curly braces {} runs, or executes.
- If the condition evaluates to false, the block won’t execute.

Let’s make an if statement.


Let’s make an if statement.

### Instructions
Checkpoint 1 Passed
1. Using the let keyword, declare a variable named sale. Assign the value true to it.

To create a let variable, follow the syntax below:
Hint
```
let sampleVar = true;
```
true is not a string, and therefore does NOT need quotes around it.

Checkpoint 2 Passed
2. Now create an if statement. Provide the if statement a condition of sale.

Inside the code block of the if statement, console.log() the string 'Time to buy!'.
Hint
An if statement has 3 parts: the if keyword, a condition wrapped in parentheses (), and a code block wrapped in curly braces {}.
```
if (conditionGoesHere) {
  // Code to execute if the provided condition evaluates to true
}
```
Checkpoint 3 Passed
3. Notice that the code inside the if statement ran, since 'Time to buy!' was logged to the console.
Hint
Below the sale variable declaration, but before the if statement, reassign sale to false. Run your code and observe what happens, we’ll be changing this behavior in the next exercise.

There shouldn’t be anything that is printed to console after you reassign sale to false.


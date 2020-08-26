# Explore the tech!
In today's blog, I am going to discuss some topics related to ** Programming in Javascript**. So, _let's get started!_

### 1. What is a _Script_, and how to write one?
A script is a series of instructions that a computer can follow step-by-step to achieve a goal, Just like recipes, handbooks and manuals. Then, a browser can use different parts of the script depending on how the user interacts with the webpage.

To write a script, the developer need to first state goal and then list the tasks that need to be completed to achieve it. In other words, the developer must Start with the big picture of what he wants to achieve, and break
that down into smaller steps, as the following:
  1. Define the goal.
  2. Design the script: using **flowcharts or steps**.
  3. Code each step: each step for every task shown in a flowchart needs to be _written_ in a language the computer can understand and follow.
  
  In conclusion, for someone who wants to learn a programming language, he must start learning how to think like a computer. Then, get fimiliar with the **vocabulary** and **syntax** of the language.
  
  
  ### 2. Expressions in Javascript:
  An _expression_ results in a single value. Generally, there are two types of expressions:
    1. Expressions that just assign to a value or a variable. `var color = 'beige';`
    2. Expressions that use multiple values to return a single value. `var area = 3 * 2;`
 Basically, expressions rely on _operators_ which allow developers to create a single value from one or more values. The following are the types of used operators:
  * Arithmetic operators. `area = 3 * 2;`
  * Logical operators. `buy= (5 > 3) && (2 < 4);`
  * Assignment operators. `color = 'beige';`
  * String operators. `greeting= 'Hi 1 + 'Mol ly';`
  * Comparison operators. `buy = 3 > 5;`
  
  
  ### 3. What is a _Function_?
  Functions let the developer group a sequence of statements together to perform a specific task. If different parts of a script repeat the same task, the function can be
reused. To declare a function, it must be given a name, writing the statements that make up the task required from the function in curly brace `{ }`. 
**Example:**
`function updateMessage() {
var el = document.getElementByld('message'};
el .textContent = msg;
}`
  + `function updateMessage()`: fuction keyword and name 
  + `{var el = document.getElementByld('message'}; el .textContent = msg;}`: code block (function body).
To call a function, the name of the function is written like this: `updateMessage();`. But if the function returns a value or contains parameters, they must be included in the call. For example, if the function returns a value, the function must be assigned to a `var` first: `var result=updateMessage();;`, so that the output can be stored in that variablr. Also, if the function contains parameters, it would look like this: updateMessage(height, width);;



 

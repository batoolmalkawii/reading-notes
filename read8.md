# Explore the tech!
In today's blog, I am going to be talking about **Operators and Loops** in _Javascript_. So, _let's get started!_.

### 1. Comparison and logical operators:
Comparison operators are used to compare 2 values to see if they are equal to each other or not. Comparison operators return a single value of `true` or `false`. The following is a list of the comparison operators used in _Javascript_:
* `==`: is equal to (compares the value, not the data type).
* `!=`: not equal to.
* `===`: strict equal to (compares the value and the datatype).
* `!==`: strict not equal to.
* `>`: greater than.
* `<`: less than.
* `=>`: greater than or equal to.
* `<=`: less than or equal to.

Also, _Javascript_ uses a list of logical operators to compare the results of more than one comparison operator. Examples of logical operators are the following:
* `&&`: and (returns true if both are true).
* `||`: or (returns true if one is true).
* `!`: not (returns true if the result is false).

### 2. `for` and `while` loops:
  1. `for`: tells the code to execute for a cpecified number of times according to some condition in the _counter_. The condition is made up of 3 parts as follows:
  
   + initialization: `var i = 0;`.
   + condition: `i < 10;`.
   + update: `i++;`.
  In the previouse example, the first time the code runs, `i` is assigned to `0`. Then, each time the code runs, the condition `i < 10;` is checked. If `true`, the code inside the loop is run and the value of `i` is increased by `1` in the _update step_.
  
  2. `while`: the difference between `for` and `while` is the structure of the loop. In `while`, it is like telling to code to keep running until the condition is no longer `true`.
  
   + condition: `i < 10;` (written before the body of the loop).
   + update: `i++;` (written after the body of the loop).

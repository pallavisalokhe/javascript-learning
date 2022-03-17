# Javascript Learning

From codecademy: https://www.codecademy.com/learn/introduction-to-javascript

## Introduction to Javascript
- console.log() used to print the message
- math.random() used for print random value 0 to 0.99 not for 1
- math.floor() print largest integer
- Math.ceil()used for returns the smallest integer greater than or equal to a decimal number.
- by using Number.isInteger() on the built-in Number object that checks if a number is an integer.
- for single line use // and multiple line use /* */
- by using .toUpperCase() string return in capital letter
- By usind .trim() we remove the space before and affer the string
## Variables
- for storing and holding the data
- for declaring variable use var,let,const
- Comparison operators, including <, >, <=, >=, ===, and !== can compare two values.
- logical operator(OR=||,and=&&,not=!)
-  javascript supports arithmetic(+,-,*,/,%) and assignment operato(+=,-=,*=,/=)
-  ++ is increment operator and -- is decrement operator
-  + operator can be used to combine two string values even if those values are being stored in variables
-  The type of operator checks the value to its right and returns, or passes back, a string of the data type.
## Conditional
-  If statement is evaluate when condition is true otherwise it is not executing 
- else statement is executing when if condition is fail
- elseif clause consist many else if conditions 
- Falsy values include false, 0, empty strings, null undefined, and NaN. All other values are truthy
- we can use a ternary operator to simplify an if...else statement.We use expressions follow the ? and are separated by a colon :.
- A switch statement can be used to simplify the process of writing multiple else if statements. The break keyword stops the remaining cases from being checked and executed in a switch statement.
## Functions
- there are many way to create function. Functions can be passed one or more values and can return a value at the end of their execution. 
  - function declaration: It consist function keyword,Identifier,function body.
  - calling a function: When a function is called, the code inside its function body runs.We can call the same function as many times as needed.
 - parameters and arguments:parameters are vaiables within function and The values that are passed to the function  called arguments.It can be values or variables.
 - Default parameter:when an argument is not passed into a function it allow parameters to have a predetermined value .
 - return
 - Helper function:helper functions can help take large and difficult tasks and break them into smaller and more manageable tasks.
 - A function with no name is called an anonymous function. 
 - A function expression is often stored in a variable in order to refer to it.
   :syntax=const variableName = function(paramGoesHere){
};
-Arrow function:Arrow functions remove the need to type out the keyword function every time you need to create a function.
## scope
## Array
- Array  used for making lists. Arrays can store any data types including strings, numbers, and booleans.
- array that holds all the same data types or an array that holds different data types.using []  literal.
- Accessing Elements includes zero-indexed meaning the positions start counting from 0 rather than 1. Therefore, the first item in an array will be at position 0.
- update element replace previous element to new element or value
- by using .length we count the number of elements in array
- .push() allows us to add elements to the end of an array.
- .pop() removes the last elements of an array.
- You can read about all of the array methods that exist on the Mozilla Developer Network (MDN) array documentation.Array method include.join(), .slice(), .splice(), .shift(), .unshift(), and .concat() 
- .shift() is used to remove first elements in array,.unshift() used to add element in starting position,.slice() use to make a list elements into array element,By using .indexOf() we find the index number of element
- When an array contains another array it is known as a nested array.
## Loop
- repeats a set of instructions until a specified condition
- When we have a loop running inside another loop, we call that a nested loop.
- Loops perform repetitive actions so we don’t have to code manually every time.
- For Loop consist if the condition is true the code  will run, and if it evaluates to false the code will stop.
 -  syntax :for (let counter = 0; counter < 4; counter++)
     {
       console.log(counter);
     }
- looping is reverse means  when printing for loop to 3, 2, 1 then we use this concept
- each element in an array, a for loop should use the array’s .length property in its condition.
- while Loop consist
 - syntx:let counterTwo = 1;
  while (counterTwo < 4) {
    console.log(counterTwo);
    counterTwo++;
    }
    Do while Loop 
syntax:
let countString = '';
let i = 0;
 
do {
countString = countString + i;
  i++;
} while (i < 5);
 console.log(countString);
## Iterator

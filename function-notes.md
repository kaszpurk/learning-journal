# Programming with JavaScript

## Intro & Scripts
JavaScript allows you to:
- Access the content of the page
- Modify the content of the page
- Program rules or instructions the browser can follow
- React to events triggered by the user or browser

Examples:
- Slideshows
- Forms
- Reload part of the page
- Filtering Data
*Scripts are series of instructions that your computer follows to achieve a goal*
> Scripts are made up of instructions a computer can follow step-by-step ~Jon Duckett, JavaScript & JQuery, pg.15
### Writing a Script
- Define the Goal
- Design the Script
- Code each step
*Tip: Use flow charts to understand the path of the user*

## Expressions & Operators
An expression evaluates into results. There are two types of expressions
1. Expressions that just assign a value to a variable
1. Expressions that use two or more values to return a single value
Expressions rely on operators; allowing programmers to create a single value from one or more values

## Functions
A function will not work unless you name or call it
> Functions let you group a series of statements together to perform a specific task. If different parts of a sscript repeat the same task, you can reuse the function ~Jon Duckett, JavaScript & JQuery, pg. 88

- Grouping together statements are not always executed when a page loads
- Functions store the steps needed to achieve a task 
    - This allows a task only when a user interacts with a specific element of the page
- Code Block: Steps that a function needs to perform for the task
- Parameters: Pieces of information that pass to a function
- Return Value: Expected outcome
- Declaring a Function:
    - Function Keyword (e.g. function)
    - Function Name (e.g. SayHello())
    - '{'
    - Code block - inside the curly braces (e.g. document.write('Hello')
- Once a function is declared, you can call the function with just one line of code:
    - Call Function: e.g. sayHell();
- Functions that need information
    - Parameters indicate what is need to be known in parentheses
    - These are used like variables within a function
        - e.g. 'function getArea(width, height) {
            return width * height;
        }'
- Calling functions that need information
    - Arguments as value: when a function gives a Number
    - Arugments as Variable: when you specify what the variables are
- Parameters vs. arguments
    - Parameters are calling specifically what is being called
    - Values passed into the code are arguments
- Getting a Single Value out of a Function
Some functions return information to the code that called them, providing a result.

'&&' means 'and'
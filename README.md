# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

- .map(): loops through an existing array and creates a new array without affecting the existing one. It is best used for converting data.  You should use .map() when you need to write conditionals and a return statement when trying to convert data

- .reduce(): also automatically loops through data but does not return a new array. Instead it returns a single value.  You would want to use reduce() when working with numerical data (ex: to get a count of the data), but it is usually used with multiplication and addition

- filter(): Like .map(), this method automatically returns a new array without manipulating the original. However, it does not include conditional statements.  The return statement is considered the conditional statement. If the return statement is true, it will return. If it is false, it won't. Because of this, filter() needs a return statement.  You would use filter() when you want your data to equate to true or false.

2. Explain the difference between a callback and a higher order function.

- Higher order function: a function that receives another function as parameters. 

- Callback function: a function that gets passed into a higher order function as an argument.
ex: function higherFn (callbackFn) {} 

3. Explain what a closure is.
A closure happens when a nested function reaches out to the outer function to grab a variable defined in the outer function

4. Describe the four principles of the 'this' keyword.

i) Window Binding : if "this" hasn't been bound to any particular object (been given any context), it will return the default global object (the window). 

ii) Implicit Binding : "this" refers to everything left of the dot when the function is invoked.  In this case, "this" is implied to refer to the objects with methods

iii) Explicit Binding : "this" is explicitly told what it should be using with..
 - .call() : Immediately invokes the function and arguments are passed one by one
 - .apply() : Immediately invokes the function. Arguments are passed as an array
 - .bind() : Arguments are passed one by one but it will not immediately invoke the function. It instead returns a new function to be invoked later

iv) New Binding - "new" will invoke a function and let "this" know to bind the new object to that function

**Arrow functions are never used with "this" since they do not bind



5. Why do we need super() in an extended class?
"extends" and super() essentially replace object.create and .call(). It allows the child function to inherit the keys from the parent, extends tells super what to apply that to

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Go into canvas and connect your reop to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/ master your codegrade score will update each time you make a push.


### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/bloomtech/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://notion.so.bloomtech.BloomTech-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) See part 2, submitting an assignment with codegrade

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

    .map() is used to alter something about an array and return a new array, you might use .map() how we did to convert the animal names to lowercase, with item.animal_name.toLowerCase(), which changes all the names to lowercase and returns that new array. 
    
    Next, .reduce() is used to return a single function, usually a total of some sort or maybe an average. You might want to calculate the total paintings made across an array of artists, and .reduce could comb over the array and return a running total of paintings painted. 
    
    Finally, .filter() is like .map() in that it also returns a new array, however, .filter() checks for a boolean statement as it goes over the main array, and then creates the new array based on whether the data was true for that check or not. For example, if you want to see cities with a population above 500,000, you could filter for item.population > 500,000 and then the new array would have only cities with a higher population than that. 

2. Explain the difference between a callback and a higher order function.

    A callback function that is made to be passed into another function(the higher order function). The higher order function takes that callback function as an argument and utilizes it. Additionally, higher order functions can return functions.

3. Explain what a closure is.

    Closure is when an inner function reaches out to an outer function, because with scope an inner can reach outwards but not the opposite. When a function is inside another function, it has access to all the outer function's variable, and if it needs to reach out that would be closure.

4. Describe the four principles of the 'this' keyword.

    -The first principle, Window Binding, states that if 'this' has no context, it attaches to and returns the window, which is not something we want (maybe rarely, but normally not). So if 'this' doesn't know what it is a part of, it defaults to the window. 

    -The second principle is Implicit Binding, which may be the most straightforward principle, and it states that whatever is to the left of the dot when the function is used is what 'this' refers to. If we have a speak method in a object for Bob for example, Bob.speak() would mean 'this' is Bob and Bob would say/return whatever the speak function message is.

    -Thirdly, Explicit Binding. Explicit binding allows us to choose what to we want our 'this' to refer to, using .call(), .apply(), and .bind(). .call() lets us pass in one argument at a time, .apply() passes the arguments at once as an array, and .bind() is also one at a time, but it makes a new function instead of invoking the current one. 

    -Finally, New Binding. When we create a new object using a constructor, new binding states that 'this' now will point to the 'new' object.

5. Why do we need super() in an extended class?

    We have to use super() to access the parent constructor, by passing in the arguments we want to utilize in the super(args) keyword. We need to use super before we can use 'this' to make 'this' point to that object. 

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

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
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)


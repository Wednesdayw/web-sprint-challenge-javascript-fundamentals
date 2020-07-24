# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL if you need direction.

_You have **three hours** to complete this challenge. Plan your time accordingly._

## Introduction

You will notice there are several JavaScript files being brought into the index.html file. Each of those files contain JavaScript problems you need to solve. If you get stuck on something, skip over it and come back to it later.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

### Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead as the evaluate your solution.

## Interview Questions

Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. You might prepare by writing down your own answers before hand.

1. Briefly compare and contrast `.forEach` & `.map` (2-3 sentences max)
   .forEach iterates through every item in an array without stopping. It doesn't return a new array automatically and does not need the return keyword. .map converts data, returns a brand new array it doesn't manipulate the original and does require a return statement.

2. Explain the difference between a callback and a higher order function.
   Higher order functions can receive other functions as parameters, callbacks are the functions that are passed into higher order functions as arguments. Callback functions are passed in, higher order functions receive.

3. What is closure? A function and its lexical environment (the variables that it uses).

4. Describe the four rules of the 'this' keyword.
   Simple Function Call/Window/Global Object Binding/Default Binding- when in the global scope, the value of "this" will be the window/console Object.
   Implicit Binding- automatically implied that 'this' is specific to something. The most common rule, when a function is invoked look to the left of the dot, that's what 'this' refers to, only applies to objects with methods.
   Explicit Binding- Call - will immediately invoke the function .call you pass in your arguments 1 by 1
   Apply- will immediately invoke the function / .apply you pass in arguments as an array
   Bind - you pass in arguments 1 by 1, but it does not immediately invoke the function, instead it returns a brand new function that can be invoked later
   all of the above allow us to explicitly tell JS what the 'this' keyword is
   new Binding - using the new keyword constructs a new object and 'this' points to it
   -when a function is invoked as a constructor using the new keyword 'this' points to the new object that's created.

5. Why do we need super() in an extended class? It's important because of inheritance, the super keyword refers to the parent class, it is used to call the constructor of the parent class and to access the parent's properties and methods. 

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade.

## Instructions

### Task 1: Project Set Up

> This section should include instruction for the sprint challenge. These should only cover things that are _not_ being evaluated by the challenge itself, e.g. environment/project setup, link to a starter project, etc. In general, this will be the following Git fork, clone, branch, commit, push, create pull request flow, though may need to be adapted for some specific challenges.

- [x] Create a forked copy of this project
- [x] Add your team lead as collaborator on Github
- [x] Clone your OWN version of the repository (Not Lambda's by mistake!)
- [x] Create a new branch: git checkout -b `<firstName-lastName>`.
- [x] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly
- [x] Push commits: git push origin `<firstName-lastName>`

### Task 2: Project Requirements

Your finished project must include all of the following requirements:

**Pro tip for this challenge: If something seems like it isn't working locally, copy and paste your code up to codepen and take another look at the console.**

#### Task A: Objects and Arrays

Test your knowledge of advanced array methods and callbacks.

- [x] Use the [arrays-callbacks.js](challenges/arrays-callbacks.js) link to get started. Read the instructions carefully!

#### Task B: Closure

This challenge takes a look at closures as well as scope.

- [x] Use the [closure.js](challenges/closure.js) link to get started. Read the instructions carefully!

#### Task C: Prototypes

Create constructors, bind methods, and create cuboids in this prototypes challenge.

- [x] Use the [prototypes.js](challenges/prototypes.js) link to get started. Read the instructions carefully!

#### Task D: Classes

Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.

- [x] Use the [classes.js](challenges/classes.js) link to get started. Read the instructions carefully!

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

### Task 3: Stretch Goals

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements!

## Submission format

Follow these steps for completing your project.

- [x] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's Repo). **Please don't merge your own pull request**
- [x] Add your team lead as a reviewer on the pull-request
- [ ] Your team lead will count the project as complete after receiving your pull-request

# Sprint Challenge: Advanced CSS and Intro to JavaScript - Influential Artists

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored advanced CSS and introductory JavaScript concepts. During this Sprint, you studied responsive web design, variable declaration, conditionals, loops, functions, arrays, and objects. In your challenge this week, you will demonstrate proficiency by creating a website of influential artists with data from an object.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. Your work reflects your proficiency in Responsive Design, and JavaScript Basics.

## Introduction

In this challenge, you will use a data set of artists to build an "influential artists" webpage. This data comes from a set of "50 influential artists" on [Kaggle](https://www.kaggle.com/ikarus777/best-artworks-of-all-time). We have reduced the data to just 20 artists to make it slightly easier to work with.

### Commits

Commit your code regularly and meaningfully.

## Interview Questions

### (please edit this file and write your answer below each question.)

Please answer the following questions below, you may edit the readme file to include your answers below the question.

1. How would you describe acessibility on the web to someone new to programming?

   - I'd probably start the conversation by giving context on how important it is for what you program to be accessible to all. Per the WHO, over a billion people in the world have some type of disability. This can include a long list of things, some things most people aren't conditioned to think are disabilities - it can be anything that prohibits one to experience anything on the web. Visual impairments, hearing impairments, mobility impairments, and cognitive impairments all fall under this. But even a user, with say, a poor internet connection could fall under this. Programming with an empathetic nature and thinking of how your products are accessed by as many people as possible is the first step in creating something truly accessible on the web.

2. Talk about 3 different things you can do to ensure your website is accessible.

   1. Practicing the use of semantic HTML, which is basically giving your code structural meaning and the provides the ability for fellow coders and automated processes the ability to easily understand and display code, for example, for SEO purposes (search engine optimization) to make your work easier to find.

      - An example of this would be to use '<section>' when appropriate instead of '<div>' which essentially in itself gives more meaning that this is a section and not just a block of code. That being said there are times when you need to utilize '<div>', but the key is isolating the use to when only necessary.

   2. Make sure your web experience is effectively working on not only desktop by a myriad of mobile devices - use viewport and media queries effectively and think how your code is being viewed.

   3. Balancing a great web experience with avoiding heavy intensive processes - not everyone if going to have fiber optic level internet speeds. Think about your animations and size of each screen that is being rendered.

3. How would you explain the concept of a variable to someone new to programming?

   - Variables are a way to easily store data to be able to be called later on for various purposes. There are three main types from what we've learned so far: '<const>' '<let>' and '<var>'. All three have their place and have different use cases.
     - for example, var dog = 'Roger'; is a way to store the name 'Roger' into the variable dog to so you can just utilize dog in future functions or processes later on in what you're writing.

4. What is the purpose of using functions in code?

   - In the simplest sense, a function is a piece of code designed to accomplish a task. You can then "invoke" this function, which is basically just another way of saying calling it at a later time through various ways. You can preview the function through utilizing console.log or actually run the process you wrote the function for via using the return word, which will execute the code then stop executing after. Functions comprise of a name, parameters, and arguments which specify the detail of the previously listed parameters.

5. How do you access a key inside of an object inside of an array?

   - We would enter object.key to access the value of any particular key within that key in the object inside of an array.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade.

## Instructions

### Task 1: Project Set-Up

Follow these steps to set up your project:

1. Fork the repo
2. Go into canvas and connect your reop to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
   NOTE: tests will run in the JavaScript portion of this challenge only.
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/ master your codegrade score will update each time you make a push.

### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png 'Split Terminal')

Inside of your second terminal type `npm start`
![alt text](assets/npm_start.png 'type npm start')

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png 'your terminal should look like this')

### Task 2a: Minimum Viable Product - Responsive Design

_Before you jump in, take 10 minutes to review the code that has already been provided for you. Take time to see how the home page was built. During this time, [Review the provided design files](design/). You have been provided all content necessary in the [index.html file](index.html) and basic styling in the [index.css file](css/index.css)._

- [ ] Ensure your website is responsive at 500px such that your styles match the [mobile design file](design/Mobile.png).

### Task 2b: Minimum Viable Product - JavaScript

Navigate to `index.js` and complete the MVP challenges. Note that you need to scroll past data (or collapse data in VScode) to find the challenges below.

## Resources

📚[Best Practices for Responsive Design](https://www.browserstack.com/guide/responsive-design-breakpoints)

🤝[W3 Schools - Responsive Design](https://www.w3schools.com/html/html_responsive.asp)

👀 [Styling with HTML and CSS](https://www.w3schools.com/html/html_css.asp)

🦄 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-2-Study-Guide-16f656025c8744458addb068e6348101)

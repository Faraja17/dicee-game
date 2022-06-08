# Dicee Game

Descripton: The Complete 2022 Web Development Bootcamp, Section 12: Boss Level Challenge 1 -The Dicee Game - Dr. Angela Yu
 
I will document my progress in this project through my commits and through the contents of this README file here on GitHub.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)
- [The Directions](#frontend-mentor---qr-code-component) 

## Overview

This assignment involved using query selectors to manipulate the DOM in creating a simple dice game. Dr. Yu provided completed HTML, CSS, and image files. My job was to program the script to get the dice rolling and to announce the winner.


### Screenshot

| | 
|:--:|
| [![Image of Dice Game on Different Devices](https://raw.githubusercontent.com/Faraja17/dicee-game/main/Screen%20Shot%202022-06-08%20at%2010.21.35%20AM.png)](https://ui.dev/amiresponsive?url=https://codepen.io/faraja17/full/WNMKVpq) |
| [Direct Link to Dicee Game on Am I Responsive Website](https://ui.dev/amiresponsive?url=https://codepen.io/faraja17/full/WNMKVpq)|


### Links

- Live Site URL: [Play on Codepen!](https://codepen.io/faraja17/full/WNMKVpq) Refresh browser for each new round.

## My process
I started out by creating random numbers for the dice using `Math.floor(Math.random() * 6);` At the time, I knew that this would generate numbers from 0 to 5, but I didn't take the time to research how to change it to 1 to 6. I gained a refresher of adding `+ 1` upon viewing the solution later on.  Instead, I wrote an if statement for each possible die roll starting with if the random number was zero, the die image displayed should be 1. I used the query selector to take each default from the HTML and set its src attribute to the correct random number outcome. Next, I wrote code to calculate and display the outcome of the round, again using the query selector to change the inner HTML of the default `h1`.  Finally, I added meta data and media queries to step it up a notch and make the game responsive.


### Built with

- Semantic HTML5 markup
- CSS 3 properties
- JS ES6

### What I learned

- randomization and logical operators
- loops, collections and conditionals
- strings and numbers
- JS expressions, operators, statements, and declarations
- DOM manipulation
- query selector

I also learned that as a programmer, I need to create a balance between concise and readable code. I was very surprised when I saw that although my program worked, my code was very different from the solution. This was because I had tediously written a line of code for each die outcome (you can view my code on code pen). In the solution, Dr. Yu instead used concatenation to randomize the picture. I realize that I must learn to think in this way, whenever possible, using clever logical ways to reduce the lines of code--let the code do the work for me! Dr. Yu also pointed out that long complex single lines of code are not good for readability, so it is good to find a balance.

### Continued development
 
I can apply what I learned about query selection and DOM manipulation to my Rock, Paper, Scissors game!

## Author

Faraja Thompson

- [My Personal Website](https://faraja17.github.io/my-website/)
- [My Blog: Teacher to Techie](https://faraja17.github.io/)
- [Faraja Thompson, M.Ed. on LinkedIn](https://www.linkedin.com/in/faraja-thompson-m-ed-70885b8/)

## Acknowledgments

I'd like to acknowledge my son and mentor [DeForestt Thompson](https://github.com/DeForestt).  His steadfast support and encouragement keep me motivated!  Thanks for forcing me to use the command-line, Son <3 <3 <3.

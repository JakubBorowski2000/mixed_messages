# Mixed Messages Portfolio Project - Random Quote Generator

## Contents
* [About](#about)
* [Overview](#overview)
* [Implementation](#implementation)
* [Technologies](#technologies)
* [Setup](#setup)

## About
First project of the codecademy pro career path **"Full Stack-Engineer"**. After completing Node, JS and version control with GitHub we were tasked with creating an app that generates randomized messages using Javascript. I decided to add a bit of HTML and css on top of that to make it more user friendly.

## Overview
For this project, you will build a message generator program. Every time a user runs a program, they should get a new, randomized output. You’re welcome to take the project in a couple of different forms, like an astrology generator, inspirational message, or nonsensical jokes. To make your program truly random, the message that it outputs should be made up of at least three different pieces of data. Take what you know of JavaScript syntax so far to build the program and customize it to your liking.

### Project Objectives:
* Build a message generator program using JavaScript
* Use Git version control
* Use command line
* Develop locally on your computer
### Prerequisites:
* JavaScript
* Git and GitHub
* Command line

## Implementation
I decided to create a random quote generator that has multiple questions and statements to choose from as well as a list of famous celebrities to assign the quote to. The program first creates a random sentence chain of length between 1 - 3. For each number in the chain the code will assign either a question or a statement to it:
> Statement - Question - Statement <br>
Question - Statement <br>
Question - Question <br>
etc.

The code then takes the array with this chain and creates a quote depending on the word there. If the word refers to a question a random question is added to the quote, the same is with the statement. Once that is done a random celebrity is added on to the end.

The quotes are outputted like this:
> Is free will real or just an illusion? The first computer was invented in the 1940s. - Eddie Murphy

Question - Statement - By

>There's a giant fish with a transparent head. - Terrence Howard

Statement - By

>Life is short. Does absolute power corrupt absolutely? Is the meaning of life the same for animals and humans? - Rachel Weisz

Statement - Question - Question - By

## Technologies
Project is created with:
* Node.JS v14.15.4
* bootstrap 5.0.0-beta2

## Setup
To run this project, simply download all files that come with project and open index.html.

Or in GitBash type when inside the mixed_messages folder:

```
$ node .\nodeScript.js
```

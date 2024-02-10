# javascript-mini-apps

This repository contains several dynamic applications using JavaScript and its various libraries, modules, and plugins. Included in these applications are uses of MongoDB, React.JS, express.js, node.js, handlebars for HTML, API integration, eslint, unit testing, and session tracking with cookies. 

---

## Anonymous Q&A

*December 2023*

This application is a question-and-answer site where users post questions and answers to these questions anonymously. This "single page app" is created using AJAX calls instead of regular page rendering and form submission.

Additional functionality includes: 

- fetch requests
- sending back JSON objects from Express
- implement routes to create an API for retrieving questions and adding new ones
- use JavaScript to trigger background requests to the API from the form submit buttons

## Blackjack

*November 2023*

This project implements a player vs. computer game of blackjack. The DOM elements are manipulated with JavaScript such that the game is replayable with no page refresh required. Although each new round generates a new, randomly shuffled deck, the program prompts the user with a text box at the beginning where the player can choose card values to be pulled to the top of the deck. The computer's logic of when to draw or stand is determined by whether the computer's hand has exceeded 18 points. 

Additional functionality: 

- manipulating the DOM by creating and adding elements
- setting DOM element attributes
- handling events with addEventListener
- stopping form submission with preventDefault
- using CSS to arrange elements with position and display
- using AJAX to make background requests

## Course Review

*October 2023*

This webpage implements form handling with GET and POST methods and allows a user to leave an anonymous course review on a class. This project uses mongoose to incorporate database implementation and tracks sessions for each new user. The following functions are also implemented: 

- use the commandline mongodb client to create a database, collection and several documents
- use mongoose to read and write data to and from mongodb from an express application
- use dotenv to load values from a file into the environment, accessible via process.env
- use pre-built session middleware to read and write data to and from an in-memory session store on a per session basis

## Web Server

*September 2023*

This project implements a basic web server with the following functions: 

- allows "redirect" configuration
- serves static files such as html files, images, and css… from a specific directory
- serves markdown files as compiled html
- displays list of links to contained files and directories if the url path is directory


## Crazy 8's 

*September 2023*

This project implements a commandline game of Crazy 8's that allows the player to play against a computer for two full rounds. The project implements the following functions: 

- uses ES modules
- incorporates unit testing to ensure functionality 

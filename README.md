# contents
* Home
 * How to play
 * Design
 * Features and user experience 
 
 * Tecnologies used
 * Fixed and unfixed bugs
 * Validation
 * Testing
 * Project creation and deployment
 * Credits
 <br>
 <br>
 <br>

 How to play




Hangman-For-All
# Home
* about Hangman-For-All
  * This implementation generates a random word from a list of words, 
and the player has to guess the letters of the word one by one.
 The game ends either when the player has successfully guessed the word, 
 or when the player has run out of guesses. In each turn of the game,
 the current state of the word is displayed, with underscores representing the letters that have not been guessed yet.
 The player can then enter a letter to guess, and the game will update 
the state of the word and display the corresponding image depending on whether the guess was correct or not.
# Features and user experience 
 * 
# Technologies Used
* Languages
* Python.
* Libraries
* random to select a random word.  word.py

# credited 
* Code Institute for the mock terminal for the deploy to a live site.
* How to add sleep for python from https://realpython.com/python-sleep/
* words.py - A list of randomly generated from free word - https://www.randomlists.com/data/words.json 
* Notepad ++ Column editor 
* For Templates free lucidchart https://lucid.app/
* Word Document with python https://youtu.be/WK-0VQsEfLA 
  https://lucid.app/lucidchart/7af783b3-f411-40d5-9e8a-e2e60a4977a6/edit?invitationId=inv_84c2610d-ede7-44d3-8c53-350bb3ca8d4f

<br>

<br>
<br>
<br>
<br>

<br>
<br>
<br>
<br>

<br>
<br>
<br>
<br>

<br>
<br>
<br>
<br>

<br>
<br>
<br>


<br>
<br>
<br>
























![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Welcome Suzan Dewitz,

This is the Code Institute student template for deploying your third portfolio project, the Python command-line project. The last update to this file was: **August 17, 2021**

## Reminders

* Your code must be placed in the `run.py` file
* Your dependencies must be placed in the `requirements.txt` file
* Do not edit any of the other files or your code may not deploy properly

## Creating the Heroku app

When you create the app, you will need to add two buildpacks from the _Settings_ tab. The ordering is as follows:

1. `heroku/python`
2. `heroku/nodejs`

You must then create a _Config Var_ called `PORT`. Set this to `8000`

If you have credentials, such as in the Love Sandwiches project, you must create another _Config Var_ called `CREDS` and paste the JSON into the value field.

Connect your GitHub repository and deploy as normal.

## Constraints

The deployment terminal is set to 80 columns by 24 rows. That means that each line of text needs to be 80 characters or less otherwise it will be wrapped onto a second line.

-----
Happy coding!
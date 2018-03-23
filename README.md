# TriviaGame
TriviaGame

Trival Game made in javascript by Sayed Hamed Rohani
==============

HTML File
--------------
I have imported jquery library from online and also lined CSS, images to the page.
The page has a background.

There are three parts for this form:
1. Start Game DIV
2. Questions DIV
3. Results DIV

which contains all the things
The Start div shows up when the page loads and others are hidden.

Timer does not start when the page loads its started when the start button is clicked!

**The questions Part:**
The questions has the same format. they are input boxes called radio buttons with similar "Names" and each question has value. if the answer is correct the value will be 1, if not the value will be 0.


Javascript
--------------
Starts a loop in the questions looking from "q1" - "q10" Names in the radio buttons.
It checks if the value of it = 1 the answer is true if not then it is not correct. if the value is undefined it means the question has not been answered.

also checks the timer and if the time goes up it alerts and the result page comes.


CSS
--------------
The box model has been made and have added background image.
also i have added some designing for the questions.

**reset CSS**
the reset css is added because it should cancel all the default styling and allow me to design my self.


THE END!
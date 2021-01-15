# Code Quiz

This project was designed as a homework assignment for UMN's coding bootcamp. 

This is a quiz application using HTML, CSS, and Javascript. This application emphasizes the use of Javascript to provide quiz questions and collect user data to determine whether the answers to a question are correct, then generates a score and makes a final page of results from the user data. 


[GitHub Repository](link)
[Deployed GitHub](link)


### Summary
HTML and CSS and Javascript documents create a quiz with multiple choice questions. 
This project focuses on the use of using Javascript to make changes to an HMTL document. 
This project utilizes appending HTML pages. 


### This project contains: 
A Start Quiz button 
- This starts a timer for the user
- Each question averages 15 seconds each for a total time of 75 seconds + 1. 

(assets/images/startQuiz.png)

An appended HTML page that features questions, and multiple choice answers
- Answers are recording using an event listener, "click" and tracks correct answers

(assets/images/q1.png)

An appended HTML page that features: 
- Final score which is calculated using time remaining
- Input area to record initials
- A Submit button that saves initials and score to local storage

(assets/images/enterInitials.png)

A Highscores HTML
- This a list summary of intials and final scores
- Clear button resets the page and local storage
- Go back button travels to the start of the quiz

(assets/images/highScores.png)



### To Execute File:
Open in browser


### Features: 
Two HTML Pages
* index.html 
    - Contains landing page to start timer
    - Appends two new pages 
* HighScores.html 
    - Retreives local data from previous page
* One CSS Page: style.css
    - Contains centering and styling for html list features
    - Contains media queries
* Two Javascript Pages contain:
    - Variables, including arrays with object
    - Event listeners
    - if/else statements
    - For Loops
    - Functions 
    - Local Storage set and get 


## Authors
Sam Meier; 

used 4-5 various "how to make a javascript quiz" sources to help catch up for this assignment while trying to practice what we learned, and other sources to produce a better readme


## Acknowledgments

UMN bootcamp provided source code and instruction on how to do this
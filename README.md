# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Dimitar Atanassov

Time spent:  6 hours spent in total

Link to project: (https://glitch.com/edit/#!/lilac-third-branch?path=README.md%3A1%3A0)

## Required Functionality

The following **required** functionality is complete:

* [ x ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ x ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ x ] Game buttons each light up and play a sound when clicked. 
* [ x ] Computer plays back sequence of clues including sound and visual cue for each button
* [ x ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ x ] User wins the game after guessing a complete pattern
* [ x ] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ x ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ x ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ x ] More than 4 functional game buttons
* [ x ] Playback speeds up on each turn
* [ x ] Computer picks a different pattern each time the game is played //Friday
* [ x ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ x ] Game button appearance change goes beyond color (e.g. add an image)//Friday
* [  ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
<img src = "http://g.recordit.co/oYqa0vNnS1.gif" width = 250> <br>
^ shows what happens when you win

<img src = "http://g.recordit.co/inHT3ENSYA.gif" width = 250> <br>
^shows pattern changes and you have 3 lives



## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[https://www.w3schools.com/jsref/jsref_random.asp]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
  When I was working on the assignment I got stuck on the part of generating a new array for the button pattern
  everytime the user pressed on the start button. After I made my function to generate a random number in a range for the array, I called it
  in the start game function but none of my buttons would be lighting up as if there were no pattern in place. So first I made sure my pattern was being
  generated by using the consol log feature of glitch and saw for some reason that the array was not being generated at all. This is when I realized what my issue was
  the global array declaration had no numbers in the array itself so when I put a few random numbers and called my function again, the pattern was now changing everytime
  I pressed start game and the program was working properly.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
  After completing this assignment I have tons of question for web development because I am brand new to the topic and would really like to learn more about.
  A question that came to mind while working on this was if I would be able to create a varibale in JavaScript that stores the players life, and take that varible and use it in my html code
  so I can display the players lives in a label, and I would want this label to update everytime the user pressed the wrong button. Another question that came to mind
  was if I would be able to put javascript code in my html code for example a function that could just update the players live straight from my html code. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
    If I were to have a few more hours on this project I would spend them trying to figure out
    how to make a button next to the start button labeled "change colors" that would change colors of every button
    every time a the change colors buttton is pressed. In addtion, I would have wanted to add a check box feature so the user could choose difficulties,
    and the difficulty would decide how fast the buttons light up and how long the user has to input the correct pattern.



## License

    Copyright [Dimitar Atanassov]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **AADIBA HAQUE**

Time spent: **3** hours spent in total

Link to project: https://glitch.com/~animated-fine-archaeology

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] When player wins, or loses, the text is shown on screen instead of on a pop-up.
- [ ] Multiple players can play and complete against each other at the same time.
- [ ] Different levels are added (and they become harder as you move up).
## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://cdn.glitch.com/caac8cd7-e679-4441-8042-a45bc8928972%2FcolorSoundGame.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

https://www.w3schools.com/css//css_font_websafe.asp

https://digitalsynopsis.com/wp-content/uploads/2019/04/beautiful-color-gradient-palettes-15.jpg

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

The instructions for creating this game were very clear and in-depth, so I did not face too many challenges in creating this submission. However, I came across
one error in my game that I fixed by debugging, or looking over and editing my code.

When I was playing the game to test if it would work, I noticed my yellow game button's sound would play, but it would not light up the button. I knew this
problem was occurring from an error in my button code. I checked my button code in all my files to find the error. I realized that in the css file,
I changed my #button4 selector to #button4, #button4.lit instead of changing my #button4:active selector to #button4:active, #button4.lit .
After editing my code to fix the error so that #button4.lit was typed after #button4:active selector, I tested my game again by playing a demo and found that 
my error was fixed. Debugging my code by checking over my code with attention to detail and making sure my syntax and functionality of my code were accurate by referencing the document
helped my overcome this challenge.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

After completing my submission, I was very interested by the use of multiple languages and files to create the webpage/game. 
I am curious about how javascript, html, and css work together on a webpage and how I can continue to code in web development so that
I can use different languages interdependently.

I also want to know more about the uses of web development -- What else can web development be use for besides games and websites? How can we make a social
impact through web development? What does the work life and day-to-day activities or long-term projects of a web developer look like? How does front-end and back-end differ? 
Is web development used in other sectors of tech, such as data science? If so, how?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had more time to work on this project, I would assess and clean up my code so I do not have repetitive code (I could put repetive code in javascript in a function and call it when needed).
I would also add optional features, such as playing a different pattern every round, making the speed faster as the turns progress,
adding music to the button instead of pitches, and adding a timer for the game.



## License

    Copyright Aadiba Haque

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

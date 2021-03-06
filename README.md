# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Jeff Chen

Time spent: 3 hours spent in total

Link to project: https://glitch.com/edit/#!/cumbersome-scarlet-hyena?path=README.md%3A1%3A0

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
<img src="http://g.recordit.co/RvPq9qIt8O.gif" width=750><br>


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I used the following websites:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random  For how to use Math.random
https://www.w3schools.com/cssref/css_colors.asp  For CSS colors

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
When implementing my 5th and 6th button, I struggled to find out why they weren't lighting up when the random sequence was playing. This was because
when I copy and pasted over the structure in the css files for the other buttons, I failed to change the #button.lit attribute to the correct button 
numbers. I soon found this out when I was debugging and looking through my code however, and changing the values to the correct ones instantly fixed it.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I would like to learn more about how other animations are used in certain websites, such as smooth transitions when moving to different parts of a website, or when the user
hovers over a dropdown menu. I have always been interested in learning how to do those kinds of styling options, and doing this project has made me exicted to continue learning 
web development.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had longer to work on this project, I would add more of the additional functionality, as well as implement a more unique styling. The reason I named my game "Jeff" was because I was
basing it off of the original game "Simon", and I thought using another first name for it would be a fun spin off. I would have liked matched the styling to be more similar to the original game, with
the buttons all in a circle, and have the buttons be shaped similarly to the original game.



## License

    Copyright Jeff Chen

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

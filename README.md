# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Christian Reyes**

Time spent: **5** hours spent in total

Link to project: https://glitch.com/edit/#!/dandy-descriptive-tricorne

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
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Adjusted how long to hold each clue's light/sound, how long to pause in between clues, and how long to wait before starting playback of the clue sequence
- [x] Adjusted the alerts given when you lose and when you win
- [x] Made the pattern longer to make the game harder

## Video Walkthrough

Here's a walkthrough of how the game works:

![](https://i.imgur.com/nde3nZ8.gif)




## Reflection Questions
1. *If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.*
    https://www.w3schools.com/cssref/css_colors.asp

2. *What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)*

    The biggest challenge I had when I was building the game was getting the buttons to switch from start to stop or vice versa when clicking on them. I tried to look for
  any small errors like spelling mistakes or something with missing closing tags or brackets, but after all my
  attempts the buttons still would not swap. I decided to move on and try to fix it later, and started working on the sound for the buttons. When that didn't work,
  I felt very discouraged and wasn't sure if I would be able to complete the game. Luckily, I had been working on different projects in one of my classes that deal with
  creating sound through code, and I remembered that the browser I was using has trouble playing audio. I decided to start from scratch again on a different browser, and
  all of my problems were fixed. If I hadn't started early and broken up the game in multiple days and set goals for myself each day, I wouldn't have had the time to try
  and debug my code and fix what was wrong. Also, I was flexible with my goals and adjusted them, which was possible because I started early and broke things up.
  
3. *What questions about web development do you have after completing your submission? (recommended 100 - 300 words)*

    One question that I have about web development is what are the similarities between different ways to build web applications? I've worked a little with the ReactJS library
  and found it to be similar in some aspects but also different in others from using Glitch. Glitch is a lot easier for beginners like me, but it also does a lot of the work for you. To be specific, my question is, is there
  a set of general rules or guidelines that a user follows when using web development tools, along with the specific rules that apply to that tool, or is each web development tool unique in
  their own way? How applicable are the skills learned using Glitch to other tools that also build full-stack web apps? What are the most user friendly and powerful web development tools that
  big name companies are using?

4. *If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)*

    If I had more time before the deadline, I would go back and add all the optional additional features, even the ones that I wouldn't want to implement like adding images to the game buttons. I would want
  to go through the process of creating functions to add these features and get a better understanding of the capablities of web development. I also would like to expand the game by adding an easy, medium, and hard
  difficulty button at the start of the game. The easy difficulty would only have four buttons, and would play a maximum pattern of 6 buttons/tones with the clue playback on each turn being constant. For the medium difficulty,
  I would add six buttons with a maximum pattern of 9 buttons/tones, and the clue playback on each turn would increase slightly. For the hard difficulty, I would have 8 buttons with a maximum pattern of 12 buttons/tones, and the clue
  playback on each turn would increase significantly. Each difficulty would have 5 levels, each increasing slightly in difficulty but staying in their respective difficulty range, i.e. the hardest easy level will still be relatively easy.
  Also, each difficulty would have a leaderboard for people who have completed the most levels on each difficulty and would be shown briefly at the end of the game.



## License

    Copyright Christian Reyes

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
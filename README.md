# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Colton Sustaita-Robb**

Time spent: **4** hours spent in total

Link to project: https://glitch.com/edit/#!/planet-gainful-country
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
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

## Notes
On my code version of the web page the game works with sounds as intended but when I go over to a separate page with just the live site no sound is played. I could never fix and since it only appeared on the live site I had trouble finding the root cause with my lack of experience.

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](your-link-here)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

     N/A

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

I had an issue with getting the Start and Stop button to switch out when the other was pressed. I had messed up on adding the hidden class in the tag as well as in startGame and endGame functions. This was a relatively simple fix and all I needed to find out my mistake was use the console and log what was happening. I had initially named my stop button as "endBtn" so when I wrote both the startGame and endGame functions based off of the documentation I used the given id of "stopBtn". I fixed this just by changing the id in the html file to match the id called in the javascript functions.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

I am curious about how specific you can format web pages as well as how you can lock objects into place. I was also thinking about how some web pages have a dark mode and a light mode so I was wondering if that works based off of a button clicked type and when it is clicked the background in the css file somehow changes. I also began to wonder if, when you inspect the page, all of the html and javascript for the page is shown or if some of it is hidden behind the scenes so that we can not change it. I really enjoyed working with this and I think this type of frontend work is fun.


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had more time to work on this I would definitely attempt changing the frequency of the sounds or try adding my own sounds to the game. I would also make the turns timed and have a timer displayed with a possible ticking sound when it got low. I think as an extra side feature I would make a settings button and when that gets clicked a little menu pops up with options such as changing the volume or switching to the light mode of the web page. I think these features would have created a more unique player experience and increased the likeability of the game.



## License

    Copyright Colton Sustaita-Robb

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

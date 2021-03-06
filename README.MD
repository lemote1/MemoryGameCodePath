# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Eyob Melesse**

Time spent: **2** hours spent in total

Link to project: https://glitch.com/edit/#!/peppered-scarce-cobbler?path=index.html%3A38%3A0

![](https://i.imgur.com/mPLiOyU.gif)


## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](your-link-here)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

JavaScript cheat sheet


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

The most difficult aspect of this submission was creating the guess function from scratch. Thanks to the picture given and prior experience, the logic behind the function came naturally. However, I encountered issues while trying to create the function in JavaScript. 
I am not very familiar with JavaScript’s syntax, so I had to do some searching to understand how to write this in a manner pertinent to JS. I used a JavaScript cheat sheet to overcome this issue. Another issue I encountered was that my when I hit “Stop” it did not revert back to my “Start” button. 
After a few minutes of tinkering and trying to figure out where I had made a mistake, I realized I had used the same JavaScript syntax for my “Start” and “Stop” buttons, when the syntax for “Stop” button should not have been identical to the syntax for the start button.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

I only have one question. If someone were to only know JavaScript, HTML, and CSS, but they knew it to the point of mastery, would that be enough for them to find a job and carve out a role on a team?


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

There are several features I would include: a leaderboard, a counter visible to the user that keeps tracks of how many guesses one has made, and a timer to show how long you took to guess.



## License

    Copyright Eyob Melesse

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
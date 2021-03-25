# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Eric Thadeus Campillo**

Time spent: **1.5** hours spent in total

Link to project: (https://glitch.com/edit/#!/adhesive-oil-sneeze)

## Required Functionality

The following **required** functionality is complete:

* [Y] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [Y] "Start" button toggles between "Start" and "Stop" when clicked. 
* [Y] Game buttons each light up and play a sound when clicked. 
* [Y] Computer plays back sequence of clues including sound and visual cue for each button
* [Y] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [Y] User wins the game after guessing a complete pattern
* [Y] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [Y] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [N] Buttons use a pitch (frequency) other than the ones in the tutorial
* [N] More than 4 functional game buttons
* [N] Playback speeds up on each turn
* [N] Computer picks a different pattern each time the game is played
* [N] Player only loses after 3 mistakes (instead of on the first mistake)
* [N] Game button appearance change goes beyond color (e.g. add an image)
* [N] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [N] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](your-link-here)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I did not use any other outside resources.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
While creating this submission, I had trouble with allowing the tone of the button to play. I checked the console and saw an error pertaining to the audio. I checked the lines of javascript code that the error was
referencing and saw nothing off. I checked the message of the error and it said "The AudioContext was not allowed to start. It must be resumed (or created) after a user gesture on the page." I took that this meant that
I had to reposition the page initialization and sound to the top of the page to allow the user input to occur after that. My code was working when the initialization was at the bottom but stopped working when I finished the project.
I looked back and fixed the issue.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
After using these new languages I have a plethora of questions relating to web development such as: "How does a website create other websites?" "How does glitch load in the update to my project so seamlessly and quickly?"

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
With a few more hours to work on the project I would have created a victory song that would play at the end as a reward for winning. I would also recreate a portion of the game to make it more focused on sound and make like a "Incredibox" type game. I would have
also finished all of the optional challenges.



## License

    Copyright [Eric Campillo]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
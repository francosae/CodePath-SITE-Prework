# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Paul Franco**

Time spent: Approximately **4** hours and **30** minutes spent in total

Link to project: https://glitch.com/edit/#!/juniper-incandescent-maxilla

Link to demo: https://juniper-incandescent-maxilla.glitch.me/

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
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Increased difficulty mode by making everything sped up (Fast Mode).
- [x] Button toggles the increased difficulty, and the appearance of the button is change to demonstrate when it is on or off.
## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

Regular Mode Win Demonstration:



https://user-images.githubusercontent.com/69439997/161369172-8f5f8e96-dac0-44b2-b0fd-0ab7ce814e05.mp4



Fast Mode Win Demonstration:

https://user-images.githubusercontent.com/69439997/161366352-e3cb3a86-8069-439b-ab26-e7698eb0baad.mp4

Regular Mode Loss and Fast Mode Loss Demonstration:

https://user-images.githubusercontent.com/69439997/161366355-8f824cab-1078-465d-a96d-acba2cd91219.mp4




## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

I used W3 Schools to look at the different names for CSS colors along with the W3 Schools page to center a div horizontally so that I can center the buttons appropriately. 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

When creating the submission, I had trouble formatting the game buttons properly, including the Start and Fast Mode buttons in order for them to not overlap. I used W3Schools' page on how to center a div and read along to see how I can apply it to the challenged that I encountered.

Another challenge that I had was creating the Fast Mode of the game. I had to create a button in which when pressed could change the speed of the game and show that it had been pressed but also when pressed again could revert to the standard settings. I knew I had to use an if-else statement to detect if the button was pressed to then change the game settings. If the the changes were already made by the button, then I could revert the settings along with returning the button to the default color. In order to change the color of the button without adding a different CSS Color, I used W3Schools to learn the CSS filter properties because I believe that using the CSS brightness filter would be better than changing the color entirely like the game buttons when they are pressed. Then I used the brightness filter to darken the button when pressed to show that the Fast Mode was toggled. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

I don't have specific questions necessarily, but I am definitely interested in learning more about web development and how dynamic websites can be made and how animations could be used to make interesting games and UI for websites

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had more hours to work on this project, I would definitely look into how I can animate the buttons to move to increase the difficulty and add more buttons with different sound along with a timer and possibly a button to replay the pattern when you get stuck. Another feature would be to prevent players from pressing buttons while the pattern is playing.

A very interesting addition would be to add music in the background that goes along with the sound of the buttons to make it seem as if you are playing a song and if you miss a note you fail the game. 


## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)



## License

    Copyright Paul Franco

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

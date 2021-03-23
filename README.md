# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Prothit Halder**

Time spent: **5.5** hours spent in total

Link to project: (insert your link here, should start with https://patch-hypnotic-paneer.glitch.me/)

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
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://i.imgur.com/uNuKo2B.gif)
![](https://i.imgur.com/Ke4NMKb.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
  I looked at https://www.javatpoint.com/ for help using HTML in order to put an image in the button. I also used Figma to find colors I wanted to use, and used the HEX Codes to make my app have an aesthetic look.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
  I had trouble figuring out how to insert an image into the button. I knew I had to put the png's in the assets container, however, I did not know how to access the images in index.html.
  I then searched up how to insert an image inside a button on Google, and looked at javatpoint.com to find solutions. I learned about the "<img>" tag where you use the src= to put the image path.
  I tried putting "assets/circle.png", however the image would not show up. Using more Google, I figured out that I need to copy the link that glitch provided for each asset you upload and paste it in src="".
  Through this effort, I was able to put different shapes in each button, so people who are colorblind will find this game more accessible since the only differentiating factor before this was the color of the button.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
  I still don't understand how the DOM works exactly. I also have a question on how the "inspect" elements works. I would've liked more explanation in the tutorial. 
  I would also want to know how to make my game more dynamic including going against other players in realtime, and how to make the UI more clean and simple. 
  I would also want to learn how to go from designing and implementing the frontend and backend of an entire app from start to finish. I would also love to learn how to add animations to my webpages. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
  Currently my buttons are not in a perfect grid, so I would utilize the grid framework to make sure my buttons are always in a 2 by 2 grid no matter how big the screen size.
  I would also add the randomization feature, where every game can be any combination of the buttons to add more difficulty to the app. I would also like to include a difficulty scale where players can play using either 4, 6, or 8 buttons depending on the difficulty of easy, medium, or hard.
  This would make the game more accessible to players of all skill levels. I would also like to implement a background song to keep the game interesting throughout. 


## License

    Copyright Prothit Halder

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

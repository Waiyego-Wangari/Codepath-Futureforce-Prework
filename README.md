# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's FTL Program. 

Submitted by: Waiyego Maina

Time spent: 10 hours spent in total

Link to project: (https://glitch.com/edit/#!/catkin-serious-cloud?path=README.md%3A11%3A25)

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
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
[](https://reccloud.com/u/3z1bhcg)
![](https://reccloud.com/u/0ctx2k3)
![](https://reccloud.com/u/rozjd73)
![](https://reccloud.com/u/audbw1y)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

[I mainly used Stackoverflow to check the syntax of the code that would implement the extra features]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 


When trying to implement the feature that makes the computer choose a different pattern each time the game is played, 
I encountered the issue where I did not know how to write that code in Javascript. I had the basic idea of the structure 
that the code would need to take. With that information, I searched on google for code that randomizes a list in Javascript. 
I sifted through many solutions on the internet before I found the one that was perfect for what I wanted to implement. 
Next, I tweaked that code to fit this game’s parameters. I obtained this code from stackoverflow.com.
	Another challenge I encountered was in implementing the images on the surface of the buttons when pressed. I knew how 
  to import the images. I then searched for the HTML code to show images. Next, I wrote the basic functions to hide and show the buttons. 
  I followed the structure of the “Start” and “Stop” buttons to write these functions. After this, I implemented a series of trials and errors where 
  I would plug the functions in various parts of the HTML structure and run the code to see how it reacts. After several tries, the images started 
  behaving as expected (only showing when the button is pressed down)
	Another challenge still about the images, was finding images that would fit perfectly into the game button. This was another trial and error process 
  where I would import the image and then check to see if it fit into the button. I discovered that the images that work best for this project all 
  happen to be .png files rather than .jpeg. I am not sure if this was just a coincidence, but I now have a preference for png images for websites.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

[I would like to understand how powerful frameworks like React and Node.js can improve the functionality of a web page
such as this one. Still, on the advanced frameworks, I would like to know when they are necessary and when it might be 
overkill to use them. For example, this game functions great, so I’m curious to what degree implementing these powerful 
frameworks would be helpful rather than overcomplicating the build.
I am also curious about the complexity of developing a website that has multiple pages. This website was particularly 
simple because all the buttons are on one page, but I’m curious about how a website with multiple pages would be built.
What parts of the process will stay the same(if any) and which ones will change.
]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

[I would have implemented the last two optional features, to enable the buttons to play a melody when pressed and have a countdown 
for the user. Another feature I would implement is adding rounds to the game automatically such that there is essentially no end. 
This would then create the need for a high score feature where the user can easily see the highest number of patterns attained before.
I would also try to optimize some of the functions I added, e.g show() and hide()(which show and hide the images when the button is 
held and released respectively.). I would try to achieve this functionality using one function instead of two separate ones.
Overall this has been a really fun learning experience and has really opened up my eyes to how fun building websites cane be:)
]



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/62d3434822e34178ba9eb5827ccdb4f3)


## License

    Copyright [Waiyego Maina]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

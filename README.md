# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Eman Bahrun**

Time spent: **21** hours spent in total

Link to project: (https://glitch.com/edit/#!/glitter-learned-feet)

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

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](http://g.recordit.co/ttnCofs7Lg.gif)
![](http://g.recordit.co/6rYyLWtgEQ.gif)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

I used StackOverflow in order to search for how to randomize the pattern for the 
game. I also used w3schools.com for randomizing the pattern as well as to know
the different syntax of javascript, html and css.  



2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

    While creating the submission I faced a couple of problems. The first one wason 
how to randomize the pattern. Even though I tried to implement my code it still 
was not working. I tried searching on google, but couldn't find useful resources.
Therefore I went to the slack channel to post my question, however I just realized 
someone else was also facing the same problem, because the same question was posted
on the channel, so I looked at the solution and it was a link to StackOverFlow. The
StackOverFlow was similar, so it was helpful. I tried to understand what they did
and implement it in my code. The other challenge I encountered was with the audio.
The audio was not working, however after searching up on StackOverFlow I realized I
had to add the resume() function.

    The other problem I encountered was with the buttons. When I started the game,it
wouldn’t play the sound nor the colors. Even though the game has started there was
no action, but when I stop and start it again it would work. When I looked at the
console, I realized the clue that was playing was out of scope. Therefore, I
initialized the buttons to four, because we only had four buttons. So it started
working and playing the clues in the right manner. Therefore by searching up
resources and looking into StackOverFlow I was able to solve the problems, and get
the result I wanted to get. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
    
    After completing my submission, I have different kinds of questions about web
development. The first and most important question that came into my mind is how
broad is web development and what kind of things one can do with it. I am not that
familiar with web development, but rather with object oriented programming like C++
or other programming languages like python. Therefore while trying to do the
pre-work I was so amazed on how interactive it is as well as how easy it was to
create the buttons and the color change and all. The other question I have is how
the more complex web applications work and how the frontend really functions. Since
I am relatively new to web development, working on my pre-work made me realize how
fascinating it is and I also realized how I enjoyed making something that is
interactive. By being exposed through the pre-work to html, css and javascript I
want to learn more and work on various types of projects. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
 
    
    If I had a few more hours to work on the project, I would tweak a couple of
 things. The first one is the sounds the buttons make when they are pressed. I
 would like it to create a more musical sound. The other thing I would change would
 be the appearance of the game, for example the buttons. I would make them have
 different shapes as well as different orientation in their positions. I would also
 change the appearance of the start and the stop button. The other thing that I
 would do would be to make the pattern of the game a little bit harder. So in
 general I would change the appearance as well as the audio so that it can look
 more appealing and make the game a little bit harder. 




## Interview Recording URL Link

[My 5-minute Interview Recording](https://ucr.zoom.us/rec/share/ajXxmmxkzRloMaWLdHcbhUcRvWit0WwLKIRweLZq1XVnv3Yuog_kYfo4PaEgMPsh.N3WGvHwWoeYUh9im?startTime=1648807617000)


## License

    Copyright [EMAN BAHRUN]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

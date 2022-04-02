# Pre-work - *Memory Game*

**Working Memory Test: Sounds and Colors** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Nikan Taheri**

Time spent: **5** hours spent in total

Link to project: (https://global-receptive-saturn.glitch.me)

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
![](https://media.giphy.com/media/sl4ha34cTBWjSqPlQU/giphy.gif)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[I did not use any outside resources.]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[The greatest challenge that I encountered when creating this submission was continuously reminding myself that I’m coding in a new language and style, and that my current experience with programming languages can be expanded to a much greater extent. To be specific, the greatest challenge that I faced while coding, and especially while coding in JavaScript, was the syntactic differences between JS and my familiar languages of Python and C++. In Python and C++, I’m used to calling functions a certain way, and classes in those languages have certain nuances that do not appear in Javascript. I was surprised to see that inheritance was brought up as a sub-topic, leading me to explore more about the versatility of CSS as I came in expecting CSS to be a simple language with little crossover between what I already know. Coding in these two languages for roughly the past year has led me to adopt common conventions specific to Python and C++, so having to deal with three new syntaxes all at once really served as a difficult stepping stone for my development. In the end, I overcame this challenge by routinely reminding myself that every language is unique in its syntax, semantics, and culture, and it would be nonsensical to stay grounded on the knowledge that I have right now. Instead of limiting myself to the syntax that I’m familiar with, I decided to immerse myself in common conventions, such as ensuring a semicolon is placed after every statement in Javascript. Camelcase really caught me off guard multiple times as I was writing variable names, and it led me to multiple bugs that would have been easily fixed if I placed myself in the mindset of a Javascript programmer instead of a Python programmer. All in all, I learned that programming is not just about the ability to write code, but to adapt my own mindset based on what I’m trying to create. ]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[After completing my submission, I feel as if I left with more questions than I initially came in with. I thought that coding a website would be a walk in the part, and that I’d never interact with Javascript for ages. Little did I know that Javascript is so integral to the development and running of a webpage. One of the lingering questions that I have is how exactly do classes in Javascript work, and how do they differ from Python or C++? Considering that Javascript is a language mainly for webpage interaction, I’d assume that classes are far, far different from those in Python, but clearly they hold the same basic principles. I’m interested to understand how a programming language that works directly with webpages utilizes classes in comparison to languages that use functions and classes to build much more complex programs. This leads me to my next question; why can’t Javascript be used to build massive programs instead of web pages? Is Javascript being used for large programs right now? I feel as if it is a fairly powerful language and can be applied to many grander purposes than just website building. Piggybacking off this exact same question, why can’t Python or C++ be used to build a website instead of Javascript? Would I be able to create a .py file in Glitch and hook it up to the CSS and HTML files just like I did with JS? If that isn’t possible, I’d love to understand why because I know many other programming languages are just as powerful, if not more versatile than Javascript, and would probably find some form of use in web development. I still have a lot more questions about web development, but these are the biggest ones I’ve taken away from my submission.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[To be completely honest, if I had a few more hours to work on this project, I would first do some more research on how JavaScript, HTML, and CSS work and what other cool features these languages come with. Every programming language has its own quirks, and I’d like to watch a few videos/read a few tutorials on other interesting functions they may have. Once I study up a little bit more, I would have liked to completely overhaul how the project works and use a little bit of my own personal laboratory knowledge with working memory tests. A really effective and useful way to measure an individual’s capacity to retain information is through a memory test known as “n-back training”. N-back training involves showing the user one box/color, and then cycling through a randomized list of colors N times. For example, using the colors we already have, I would show the user the color Green as my first color. Then, in 3-back training, I would cycle through a randomized list of the four available colors, such as Blue, Red, and Green. I would ask the user what the third color is, and if they choose Green, then they are correct. Now, to make this more interesting and detract it from the original goal of N-back training, I’ll apply it to the memory game by making the user perform four N-back training cycles. Then, they come back and select the boxes that were shown. An example run-through would include
Test 1: Green, Blue, Blue, Red; red. 
Test 2: Red, Green, Blue, Blue; blue. 
Test 3: Blue, Green, Red, Yellow; yellow. 
Test 4: Yellow, Blue, Yellow, Red; red. 
The user would then be shown four boxes, and must click on “red” “blue” “yellow” and “red” in that particular order.]



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [Nikan Taheri]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
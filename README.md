# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Shakeal Hodge**

Time spent: **5** hours spent in total

Link to project: (https://glitch.com/edit/#!/climbing-root-heat)

## Required Functionality

The following **required** functionality is complete:

- [1] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [1] "Start" button toggles between "Start" and "Stop" when clicked.
- [1] Game buttons each light up and play a sound when clicked.
- [1] Computer plays back sequence of clues including sound and visual cue for each button
- [1] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [1] User wins the game after guessing a complete pattern
- [1] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [1] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [1] Buttons use a pitch (frequency) other than the ones in the tutorial
- [0] More than 4 functional game buttons
- [0] Playback speeds up on each turn
- [0] Computer picks a different pattern each time the game is played
- [0] Player only loses after 3 mistakes (instead of on the first mistake)
- [0] Game button appearance change goes beyond color (e.g. add an image)
- [0] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [0] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [0] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![1](http://g.recordit.co/QBjKlyDqdD.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

   [rapidtables.com, w3schools.com, stackoverflow.com]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

   [The first challenge I ecountered was implementing the guess function, I had trouble figuring out how to increment the user's progress.
   I also struggled on whether I should increase the user progress before or after calling the playSequence function.
   Nested conditionals often troubles me because its challenging to work through which sequence the functions will be called in.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

   [How much of web development is collaborative? A great deal of this submission is work that was built off the work
   that someone else did, even the websites that I used to complete the task built upon the work of other computer scientists.
   I understand that individual skill is important but and can be built through hard work,
   so I was just wondering how much work in the field is done collaboratively and how much of a person's coding ability is determined by talent?]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

   [If I had a few more hours I would attempt to make the time between the clues less.
   The clues currently play for longer than I think most people using a device are able to click.
   If I had more time I would try to miniize this time and gradually decrease the time given between the clues as the game progresses.
   I would also attempt to build sequences that increase in length as the player completes a sequence.
   For example if the user completes a sequence of size 4, then the next level would be size 5 or 6.
   I think by adding these two things along with changing the tones as the levels change would make the game more interesting.]

## License

    Copyright [Shakeal Hodge]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

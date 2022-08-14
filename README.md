# PacMen Exercise

#### A project for the MIT xPro course *Web Development with JavaScript*

<img src="https://github.com/lkmitx/pacmen-exercise/blob/main/images/PacMan1.png" width="40" height="40">&nbsp;&nbsp;<img src="https://github.com/lkmitx/pacmen-exercise/blob/main/images/PacMan2.png" width="40" height="40">&nbsp;&nbsp;<img src="https://github.com/lkmitx/pacmen-exercise/blob/main/images/PacMan3.png" width="40" height="40">&nbsp;&nbsp;<img src="https://github.com/lkmitx/pacmen-exercise/blob/main/images/PacMan4.png" width="40" height="40">&nbsp;&nbsp;<img src="https://github.com/lkmitx/pacmen-exercise/blob/main/images/PacMan1.png" width="40" height="40">&nbsp;&nbsp;<img src="https://github.com/lkmitx/pacmen-exercise/blob/main/images/PacMan2.png" width="40" height="40">&nbsp;&nbsp;<img src="https://github.com/lkmitx/pacmen-exercise/blob/main/images/PacMan3.png" width="40" height="40">&nbsp;&nbsp;<img src="https://github.com/lkmitx/pacmen-exercise/blob/main/images/PacMan4.png" width="40" height="40">&nbsp;&nbsp;<img src="https://github.com/lkmitx/pacmen-exercise/blob/main/images/PacMan1.png" width="40" height="40">&nbsp;&nbsp;<img src="https://github.com/lkmitx/pacmen-exercise/blob/main/images/PacMan2.png" width="40" height="40">&nbsp;&nbsp;<img src="https://github.com/lkmitx/pacmen-exercise/blob/main/images/PacMan3.png" width="40" height="40">&nbsp;&nbsp;<img src="https://github.com/lkmitx/pacmen-exercise/blob/main/images/PacMan4.png" width="40" height="40">&nbsp;&nbsp;<img src="https://github.com/lkmitx/pacmen-exercise/blob/main/images/PacMan1.png" width="40" height="40">&nbsp;&nbsp;<img src="https://github.com/lkmitx/pacmen-exercise/blob/main/images/PacMan2.png" width="40" height="40">&nbsp;&nbsp;<img src="https://github.com/lkmitx/pacmen-exercise/blob/main/images/PacMan3.png" width="40" height="40">&nbsp;&nbsp;<img src="https://github.com/lkmitx/pacmen-exercise/blob/main/images/PacMan4.png" width="40" height="40">

## Description

This is a fun exercise that lets you add multiple PacMen, and send them traveling back and forth and up and down the page, with a nice bounce effect. Created in week 7 of the course, the exercise uses a JavaScript function `makePac()` to add PacMen images at random positons on the web page, and another JavaScript function `update()` to set the velocity of the PacMen. This simulates movememt by adding the velocity to the initial position of each PacMan. A third JavaScript function `checkCollisions()` is called by `update()` to ensure that the PacMen images do not travel off the edge of the page. And finally, a fourth JavaScript function `makeOne()` is used to populate a `PacMen` array.

## How to Run

- Download the repository on your machine as a zip file.
- Unzip the file.
- Open the `index.html` file in your web browser.
- Press the buttons to play the game.
- Reload the page to reset and start over.

## Roadmap of Future Improvements

Further development of this repository could include the following:

- [ ] Allow user to input the number of PacMen to generate in a text box so that they don't have to click `Add PacMan` multiple times
- [ ] Allow user to pause movement.
- [ ] Allow user to clear the screen.
- [ ] Add dynamic boundary updating so that the user can resize their browser window and PacMen will use updated edges for reverse motion.
- [ ] If possible, account for collisions among the different PacMen.

## License Information

The MIT License (MIT)

Copyright (c) 2022 Latika Keegan

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

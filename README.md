# PacMen Factory Exercise from Module 7
## <a href="https://github.com/rd1r0cc0/PacMen">GitHub Repo for PacMen Factory Exercise</a>

<img src="./images/PacMan1.png">

## Factory for Making PacMen

When button "Add PacMan" is pressed, it calls the function makeOne() that then calls the function makePac() to randomly set the position of the new PacMan image and adds it to the "game" div.  It is then added to the array of PacMen, which keeps track of the position and velocity of each PacMan.

When button "Start Game" is pressed, it calls the function update() to make all of the PacMen start moving.  The update() function calls the checkCollisions(item) function to make each PacMan bounce off any wall it hits.


## Roadmap of Future Improvements

- Add various sizes of PacMen when 'Add PacMan' is pressed
- Make each PacMan face in the correct direction when bouncing off the sidewalls


## LICENSE

Copyright (c) 2020

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


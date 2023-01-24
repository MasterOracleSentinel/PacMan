<img src= "PacMan1.png" width='300' />



# PacMan

    Name: Coding with PacMan  

    Description: JS infused HTML file that simulates an image of PacMan going from one end of the screen to the next. 
    
    If you've ever played an arcade game, then you're familiar with Pac-Man!

This is the game where the player controls PacMan who travels inside a maze trying to eat all the dots while avoiding the colorful ghosts.

Of course, I didn't build the full PacMan game. 
But, I worked on an assignment that built a feature of this game, 
which displays and moves PacMan from one side of the screen to the other.

It was highly suggested that we used either setTimeout or  setInterval
to assist with solving the problem.

We were instructed to use setTimeout to calculate the movement of PacMan. 

But in the actual code, we were encouraged to use setInterval. 


Using setInterval I structured the function in a different way from how I
used setTimeout. 

Instead of passing in two arguments to setTimeout, I passed four arguments 
to setInterval. The first extra one is called pos, which 
stands for position, and is already set at 0 on line 2. The second extra argument is pageWidth, which was calculated on line 3.

Files-
* images folder: This folder contains the images representing Pac-Man at different stages (mouth open, mouth closed).
* index.html: This is the HTML file that displays your Pac-Man.
* pacman.js: This contains the PacMan animation JavaScript starter code.

Line 34 on the pacman.js file, has a setInterval call to run every
300 milliseconds.

The checkPageBounds function allows PacMan to reverse his trajectory once the PacMan image hits the edge of the screen on the x-axis.

Note: Based on the speed of you browser, the PACMAN image may
stick occasionally, giving the illusion that the PACMAN is gliding.

It should return to normal after a couple of seconds.

    Installation: //opensourse //

    Usage: these files can be used to teach DOM, js manipuation 

    Support: TBA

    Roadmap: TBA 
    
    License information: // MIT License

Copyright (c) [2022-2023] [K. Artis-Mickens, CEO MissionCore Software]

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
    
    


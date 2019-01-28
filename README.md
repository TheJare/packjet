# Packjet

A mini Global Game Jam 2019 entry by Javier Arevalo.

The theme is *"What Home Means to You"*. This minigame is of course a riff on
the classic [Jet Pac by Ultimate](https://en.wikipedia.org/wiki/Jetpac), the
game that made me decide to become a game developer when I was 13 years old.

[Play Packjet](http://iguanademos.com/Jare/games/packjet/)

## Notes

Your goal in the game is to pick the magenta fuel cells that drop and put them
in the rocket (gray rectangle), and repeat. Kill the orange baddies before they
hit you. Difficulty steadily grows in procedural fashion until the game likely
becomes too hard.

Controls for left, thrust and right are keys A/W/D, O/Q/P or arrow keys.
Shoot with Space, Control or M or S. I also implemented mouse control
and touch controls for mobile devices. It's harder to play like that, but
all things considered, it kind of works.

I did not get to implement graphics or most metagame niceties like game over,
multiple lives, rocket takeoff or such. I spent about 3 hours on the game,
one hour on mobile & compat, and one hour on misc stuff, spread in haphazard
half-hour sessions over the GGJ weekend. I made reasonable efforts to get this
to run well on all web browsers, including mobile browsers and the app-like
shortcuts you can create on iOS and Android.

This minigame is written in the most oldschool way possible, mostly globals and
functions. This is intentional, to sort of exercise parts of my coding brain that
are normally dormant in favor of OOP and reasonable software engineering practices.
My natural tendency immediately would be to start abstracting and make a basic OOP
framework to build on top of. Make a vector type, a rect type, all objects share
these basic properties, collision detecting based on collision groups, virtualized
collision response, etc. Yeah that's better software design but by now it's all so
automatic in my head that there's nothing to gain from doing it as an exercise.

## MIT License

Copyright (c) 2019 Francisco Javier Arévalo Baeza

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
SOFTWARE.)
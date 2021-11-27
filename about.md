# [Home](./index.md) - [About](./about.md) - [Process](./process.md) - [Gallery](./gallery.md)

## About Glider
<!-- pick a pretty photo from the project, maybe a pile of buttons -->
### Glider is a lot of things. 

It's a collection of buttons moving through the world. It's an experiment in typsetting things that probably shouldn't be typset. It's a test of how many buttons I can make before I snap. It's an art project inspired by Conway's Game of Life 

It's probably also a metaphor for something. Let me know if you figure out what it's a metaphor for. I'd really love to know.

## About Conway's Game of Life
The Game of Life is an odd game. It's played by zero players on an infinite two dimensional board and can technically carry out any algorithm. Given different starting conditions, the game can reach a steady state almost instantly or it can go on forever.
The rules of the game are surprisingly simple. From the game's [Wikipedia page](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life):
>1. Any live cell with two or three live neighbours survives.
>2. Any dead cell with three live neighbours becomes a live cell.
>3. All other live cells die in the next generation. Similarly, all other dead cells stay dead.

Just those three conditions are enough to generate amazingly complex patterns, from spaceships that traverse the board infinitely to a [simulation of the Game of Life within the game](https://youtu.be/xP5-iIeKXE8).

### The Magic of Spaceships, Meta-Life, and Turing Completeness 
Spaceships are patterns within Game of Life that will move across the board infinitely, or until they hit another pattern. Gliders are the simplest 
spaceship form, with five cells oscilating through four positions. Aside from just being interesting, gliders are incredibly useful in the Life
-within-Life linked above. The glider construct is also what makes the Game of Life Turing complete, meaning the game could theoretically 
replace a coding language like Python or Java. Alan Zucconi has an excellent [video](https://youtu.be/Kk2MH9O4pXY) demonstrating the construction of a computer in Life, from 
basic logic circuts to a Full Universal Turing Machine and an 8-bit programmable computer.



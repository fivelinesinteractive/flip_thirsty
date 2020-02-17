#Thirsty Zombie

Our zombie likes sprite and hates code. This game throws soda can sprites at the zombie where the zombie must consume (destroy) them. If the zombie consumes a "coke" sprite, it will explode and end the game. If the zombie misses too many "sprite" sprites, it will die from dehydration.  The zombie is rewarded one point for every "sprite" consumed.

**Game Algorithm**:

- create a game canvas with a width of 30 and height of 20 grid cells
- use `callback(function, time)` throw the cans
- pick a random probability for throwing a "coke"
- reward the zombie `1` point for every sprite consumed
- destroy the zombie, if
    - the zombie consumes a coke
    - the score falls below zero
- use random speeds and callback times to throw more or less cans
- use effects to make the game fun
- reset the game if the `r` key is pressed

## Prerequisites
You'll need to have flip installed, a trusty text editor handy, and the command prompt (or terminal) open to complete this tutorial. Visit [http://flip.fivelines.io](http://flip.fivelines.io) for installation instructions.


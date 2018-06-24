# water
A simple program which simulated behavior of water (flood, wave, rain, snow, etc) in a smooth landscape given as input

This project done in collaboration with Liam Dehaudt at 42.

## Features
* Switch between different water interactions with number keys on the small keyboard:
  1. Flood
    - Uniformly raising water level from outside of the landscape (fills dents when water level reaches boundary height)
  2. Wave
    - Releases a wave which swipes through the landscape from one side to another
  3. Rain
    - Rain drops from the sky and accumulates at all low points in the landscape
  4. Snow
    - Snow falls and accumulates (with more 'stickness' than rain) in the landscape
  5. Flush
    - Drains all the water from the landscape
  6. Moses
    - Moses comes with the people of Isreal, and the water reacts accordingly
* Space key to pause and resume animation
* Arrow keys to rotate the landscape (around x-axis and z-axis)
* Number keys 1-4 on top of keyboard to change color theme
* Semi-transparent water
* Perspective projection

## Compiling and running
Run `make`. An executable will compile. Currently only tested on OS X.

Run with `./fractol "Filename"`. A collection of sample input files can be found in `./maps` folder.

## Modes
* Flood
![alt text](https://github.com/conanwu777/water/blob/master/1.png)
* Wave
![alt text](https://github.com/conanwu777/water/blob/master/2.png)
* Rain
![alt text](https://github.com/conanwu777/water/blob/master/3.png)
* Snow
![alt text](https://github.com/conanwu777/water/blob/master/4.png)
* Moses
![alt text](https://github.com/conanwu777/water/blob/master/5.png)

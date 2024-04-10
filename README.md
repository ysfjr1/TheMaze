# Alx The Maze project

## Background Context
The goal of this project is to create a game using raycasting.

## Requirements

### General
- All your files will be compiled on Ubuntu 14.04 LTS, using gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4.
- We will use the gcc flags -Wall -Werror -Wextra and -pedantic.
- All your functions must be commented.
- Your functions should be maximum 40 lines long (one statement per line).
- Your functions should be maximum 80 columns long.
- No more than 5 functions per file.

### Betty
- Your entire repository will be checked using Betty.
- Don’t push any object files .o or temporary files *~, or any unused source file if you don’t want to lose points!
- It is advised to always keep a clear organization in your repository. For example, store all your sources in a src directory, and all your headers in a inc, headers or dependencies folder.

## Installation

Clone this repo:
```bash
git clone https://github.com/ysfjr1/TheMaze.git
```
## Compiling
This project makes use of gcc and make for the compilation process.

### Windows
Ensure you have gcc, and make(Can install using chocolatey). Then run the following command:

```bash 
make
```
### Linux
First make sure SDL is installed. If you haven't install SDL by running ``` make linux_install ```. Then run the following command:

```bash
make linux 
```
to compile.

### Mac
Ensure sdl is installed. Then run the following command:

```bash
make mac
```
## Running
After successfully compiling run the program using following command:

```bash
./maze MAP
```

where ```MAP``` is the name of the file found in the maps folder. You can create other maps and pass them while running program as above. Map files accept only the allowed characters.

## Controls

```W``` - Moving forward

```S``` - Moving backward

```A``` - Look left

```D``` - Look right

```Mouse move left/right``` - look left or right

```M``` - Turn off map visibility. The 2D map won't be visible on clicking

```N``` - Turn on map visibility. The 2D map will be visible again if it wasn't

***Have fun!***

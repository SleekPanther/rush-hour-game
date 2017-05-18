# Rush Hour Game

The classic board game recreated in `C++` using OpenGL

# [Download (windows only)](https://github.com/SleekPanther/rush-hour-game/releases/latest)

![](images/cover.png)

Unfortunately I can't compile code for Mac

## Demo
![](images/demo1.gif)

## Code Notes
- All board setups are stored in vectors as a list of integers, but can also be read from their respective file
  - 
- The current moves & vehicle positions are saved to the progress file: `.delete_this_file_if_program_dies`  
  Sometimes the whole program will crash & `vector` will go out of bounds if the file is corrupted
  Simply delete it & the program will create a new one
  - The 1st line in the **Progress file** is the previous score, 

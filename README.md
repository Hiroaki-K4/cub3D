# cub3D
This project’s objectives are similar to all this first year’s objectives: Rigor, use of C, use
of basic algorithms, information research etc.
As a graphic design project, cub3D will enable you to improve your skills in these
areas: windows, colors, events, fill shapes, etc.
To conclude cub3D is a remarkable playground to explore the playful practical applications of mathematics without having to understand the specifics.
With the help of the numerous documents available on the internet, you will use
mathematics as a tool to create elegant and efficient algorithms.

<br>

# My score
![cub3d](https://user-images.githubusercontent.com/51109408/123183313-43275480-d4cc-11eb-838a-96b2d6246720.png)

<br>

# Example
![cub3D](https://user-images.githubusercontent.com/51109408/123184044-d1e8a100-d4cd-11eb-873c-8a6e104d6924.gif)

<br>

# Ray casting
I used Ray casting to draw the wall. I referred to [lodev](https://lodev.org/cgtutor/raycasting.html).

<br>

# How to build
Build the files.
```
make
```
Rebuild
```
make re
```
Clean .o files
```
make clean
```
Clean all files
```
make fclean
```

# Dependencies
This program has been confirmed to work only on ubuntu. Since I use [minilibx](https://harm-smits.github.io/42docs/libs/minilibx/getting_started.html), please install the required libraries with the following command.
```
sudo apt-get update && sudo apt-get install xorg libxext-dev zlib1g-dev
```

# How to run
```
./cub3D sample.cub
```

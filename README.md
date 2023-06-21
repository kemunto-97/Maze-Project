# The Maze Project
The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world!

The Maze was written in C using SDL2 library. Development was performed using Ubuntu 14.04 LTS - gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4

On the map, the player can move in all four directions using keys W, A, S, and D.

The player can move through the maze and turn left or right as desired.

If the player hits a wall, they cannot move unless they change their direction.

The player can move in several directions and rotate at the same time.

<strong><h2>Installation</h2></strong>

Clone this repo:

git clone https://github.com/candiepih/The-Maze.git

<strong><h2>Compiling</h2></strong>

This project makes use of gcc and make for the compilation process.

<strong><h3>Windows</h3></strong>
Ensure you have gcc, and make(Can install using chocolatey). Then run the following command:

<pre>make</pre>
<strong><h3>Linux</h3></strong>
First make sure SDL is installed. If you haven't install SDL by running make linux_install. Then run the following command:

<pre>make linux </pre>
to compile.

<strong><h3>Mac</h3></strong>
Ensure sdl is installed. Then run the following command:

<pre>make mac</pre>

<strong><h2>Running</h2></strong>

After successfully compiling run the program using following command:

./maze MAP
where MAP is the name of the file found in the maps folder. You can create other maps and pass them while running program as above. Map files accept only the allowed characters.

Controls
<code>W</code> - Moving forward

<code>S</code> - Moving backward

<code>A</code> - Look left

<code>D</code> - Look right

Mouse move left/right - look left or right

<code>M</code> - Turn off map visibility. The 2D map won't be visible on clicking

<code>N</code> - Turn on map visibility. The 2D map will be visible again if it wasn't

Have fun!

<strong><h2>Directories</h2></strong>
<code>src</code>

Contains all the source code files written in C.

<code>inc</code>

Contains all the header files.

<code>maps</code>

Contains map data files. This will be used by the program to output the map layout.

<code>images</code>

Contains image files.

<strong><h3>Texture Sources</h3></strong>
Weapon

https://www.seekpng.com/idown/u2w7u2t4i1y3a9y3_call-of-duty-guns-firearms-gun-weapons-coat/

<strong><h3>Related</h3></strong>
The Maze - Holberton Project Page

<strong><h3>Authors</h3></strong>
Dianah Nyamweya kemuntonyamweya@gmail.com

![image](https://github.com/kemunto-97/Maze-Project/assets/85859798/8cf8b16f-4525-4aac-bec6-39d445365ff9)

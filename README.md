# The Maze Game
The Maze is an immersive 3D game that utilizes raycasting techniques to transform a 2D map into a visually compelling and interactive 3D environment.

Developed using the C programming language and powered by the SDL2 library, The Maze brings to life a captivating gaming experience. The development process took place on Ubuntu 14.04 LTS, employing the reliable and efficient gcc compiler version 4.8.4.

By employing raycasting algorithms, The Maze is able to generate a realistic and immersive 3D world, allowing players to navigate through intricately designed mazes. The game leverages the power of raycasting to render the walls, corridors, and objects in the environment, creating a sense of depth and perspective.

The C programming language, known for its versatility and efficiency, provided a solid foundation for the development of The Maze. The SDL2 library served as a valuable toolkit, offering a wide range of functionalities for graphics rendering, input handling, and audio integration. This combination enabled the creation of a seamless and engaging gameplay experience.

With its visually stunning 3D rendering, challenging mazes, and intuitive controls, The Maze stands as a testament to the power of raycasting and showcases the potential of C and SDL2 in game development.
# Installation
```
$ git clon https://github.com/assisi-francis/The-Maze-Project
```
# Usage
+ To launch the game, Execute ./maze or type make run
+ Once in the game, you can navigate through the maze using the up and down arrow keys. Alternatively, you can use the "w" and "s" keys to achieve the same movement effect.

+ To change the camera perspective and look around, make use of the right and left arrow keys. Similarly, the "d" and "a" keys can be used to achieve the same camera rotation functionality.
# Compilation
```
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```



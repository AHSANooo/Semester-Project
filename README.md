# Centipede Game Project

This is a simple Centipede game project written in C++ using the SFML library. The game features a player-controlled character, a centipede that moves across the screen, mushrooms that act as obstacles, and a spider enemy.

## How to Run the Game

### Requirements

Before compiling and running the game, make sure you have the following installed:

1. GNU G++ Compiler
   ```bash
   sudo apt-get install g++
   ```

2. SFML library
   ```bash
   sudo apt-get install libsfml-dev
   ```

### Compilation

To compile the game, follow these steps:

1. Navigate to the project directory.
2. Open a terminal window.
3. Run the following commands:
   ```bash
   g++ -c Centipede.cpp
   g++ Centipede.o -o sfml-app -lsfml-graphics -lsfml-audio -lsfml-window -lsfml-system
   ```

### Running the Game

After successfully compiling the game, run the following command to start the game:
```bash
./sfml-app
```

## Controls

- Use the arrow keys to move the player character.
- Press the 'F' key to fire a bullet.

## Demo Video

Watch the project in action:

[![Centipede Game Demo](https://img.youtube.com/vi/Fkm6LovkM2M/0.jpg)](https://youtu.be/Fkm6LovkM2M)

## Additional Information

- The game features background music, sound effects, and multiple levels.
- As the player progresses through the levels, the difficulty increases.
- Collect points by defeating enemies and destroying obstacles.

Feel free to explore and modify the code to enhance the game further!
```
